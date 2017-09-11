---
layout: chapter
title: Examples 4a - Simple Meters
abc: true
---

Using the following examples, determine:
- what all *simple* meters have in common
- what the top and bottom numbers mean in a simple time signature
- what *duple*, *triple*, and *quadruple* mean they follow *simple*
- how to determine where to beam in simple meters 
- a list of common meters in *simple duple*, *simple triple*, and *simple quadruple*

{% capture ex1 %}X:1
T:Common examples of simple duple meters with correct beaming
T:Meter changes are noted at the end of the previous line
M:2/4
L:1/4
K:C
G G | G/2G/2 (3G/2G/2G/2|G/4G/4G/4G/4 G/2G/4G/4||
[M:2/2][L:1/2] G G | G/2G/2 (3G/2G/2G/2|G/4G/4G/4G/4 G/2G/4G/4||
[M:2/8][L:1/8] G G | G/2G/2 (3G/2G/2G/2|G/4G/4G/4G/4 G/2G/4G/4||
[M:2/16][L:1/16] G G | G/2G/2 (3G/2G/2G/2|G/4G/4G/4G/4 G/2G/4G/4||{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

{% capture ex2 %}X:2
T:Common examples of simple triple meters with correct beaming
T:Meter changes are noted at the end of the previous line
M:3/4
L:1/4
K:C
G G G| G/2G/2 G/2G/2 (3G/2G/2G/2| G/4G/4G/4G/4 G/4G/4G/2 G/2G/4G/4||
[M:3/2][L:1/2] G G G| G/2G/2 G/2G/2 (3G/2G/2G/2| G/4G/4G/4G/4 G/4G/4G/2 G/2G/4G/4||
[M:3/8][L:1/8] G G G| G/2G/2 G/2G/2 (3G/2G/2G/2| G/4G/4G/4G/4 G/4G/4G/2 G/2G/4G/4||
[M:3/16][L:1/16] G G G| G/2G/2 G/2G/2 (3G/2G/2G/2| G/4G/4G/4G/4 G/4G/4G/2 G/2G/4G/4||{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

{% capture ex3 %}X:3
T:Common examples of simple quadruple meters with correct beaming
T:Meter changes are noted at the end of the previous line
M:4/4
L:1/4
K:C
G G G G| z/2G/2 G/2G/2- G/2G/2 (3G/2G/2G/2|G- G/2G/2 G/4G/4G/4G/4 G/2G/4G/4||
[M:4/2][L:1/2] G G G G| z/2G/2 G/2G/2- G/2G/2 (3G/2G/2G/2|G- G/2G/2 G/4G/4G/4G/4 G/2G/4G/4||
[M:4/8][L:1/8] G G G G| z/2G/2 G/2G/2- G/2G/2 (3G/2G/2G/2|G- G/2G/2 G/4G/4G/4G/4 G/2G/4G/4||
[M:4/16][L:1/16] G G G G| z/2G/2 G/2G/2- G/2G/2 (3G/2G/2G/2|G- G/2G/2 G/4G/4G/4G/4 G/2G/4G/4||{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

{% capture ex4 %}X:4
T:Some common beaming exceptions in simple meters
M:4/4
L:1/4
K:C
G/2G/2- G/2G/2 G G| G/2 G G/2 G G||
w:Ideal| Common
G- G/2G/2 G- G/2G/2| G>G G>G|]
w:Ideal| Common|{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}

