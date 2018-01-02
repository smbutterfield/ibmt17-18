---
layout: page
title: search
---

Lunr.js search draft

<script src="https://unpkg.com/lunr/lunr.js"></script>

<form class="searchall" role="search" id="search" >
  <input type="text" size="15" id="lunr-search" placeholder="Search..." aria-label="search">
  <input class="button-all" type="button" onclick="lunr_search();" value=" Search ">
</form>

<ul id="search-results"></ul>
<script>
  // https://learn.cloudcannon.com/jekyll/jekyll-search-using-lunr-js/
  // https://lunrjs.com/guides/getting_started.html
// add documents
var documents = { 
    {% for post in site.documents %}
    "{{ post.url | absolute_url | xml_escape }}": 
    { 
      "url": "{{ post.url | absolute_url | xml_escape }}",
      "title": "{{ post.title | xml_escape }}",
      "text": {{ post.content | strip_html | jsonify | replace: "\n"," " }}
    }{% unless forloop.last %},{% endunless %}
    {% endfor %}
};
// create index
var idx = lunr(function () {
  this.ref('url')
  this.field('title')
  this.field('text')
  for (var key in documents) {
    this.add(documents[key])
  }
});
// do search
function displayResults(results) {
  var searchResults = document.getElementById('search-results');
  if (results.length) { // Are there any results?
    var appendString = '';
    for (var i = 0; i < results.length; i++) {  // Iterate over the results
      var link = results[i].ref;
      var title = documents[results[i].ref].title;
      appendString += '<li><a href="' + link + '">' + title + '</a></li>';
      //appendString += '<li><a href="' + item.url + '"><h3>' + item.title + '</h3></a>';
      //appendString += '<p>' + item.text.substring(0, 150) + '...</p></li>';
    }
    searchResults.innerHTML = appendString;
  } else {
    searchResults.innerHTML = '<li>No results found</li>';
  }
}
function lunr_search() {
    var query = document.getElementById("lunr-search").value;
    var results = idx.search(query);
    displayResults(results);
}
</script>
