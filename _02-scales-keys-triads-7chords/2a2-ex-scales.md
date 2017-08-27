---
layout: chapter
title: 2a Examples - Scales and Scale Degrees - Diatonic, Pentatonic, and Chromatic
abc: true
---

The following examples demonstrate how the tune of *Happy Birthday* would be written using various scales. Scale degrees are notated below each pitch as well as solfege using movable "do". When determining your pitch collections, pay particular attention to the differences of the sixth and seventh scale degrees.

### Major

{% capture ex1 %}X: 1
T:Happy Birthday in G major
M:3/4
L:1/4
Q:1/4=90
K:G
D/2>D/2| E D G| F2 D/2>D/2| E D A| G2 D/2>D/2|
w:^5 ^5 ^6 ^5 ^1 ^7 ^5 ^5 ^6 ^5 ^2 ^1 ^5 ^5
w:sol sol la sol do ti sol sol la sol re do sol sol
d B G| F E c/2>c/2| B G A| G2|]
w:^5 ^3 ^1 ^7 ^6 ^4 ^4 ^3 ^1 ^2 ^1
w:sol mi do ti la fa fa mi do re do{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

### Natural minor

{% capture ex2 %}X:2
T:Happy Birthday in G natural minor
T:using the parallel minor to G major
M:3/4
L:1/4
Q:1/4=90
K:Bb
D/2>D/2| E D G| F2 D/2>D/2| E D A| G2 D/2>D/2|
w:^5 ^5 ^6 ^5 ^1 ^7 ^5 ^5 ^6 ^5 ^2 ^1 ^5 ^5
w:sol sol le sol do te sol sol le sol re do sol sol
d B G| F E c/2>c/2| B G A| G2|]
w:^5 ^3 ^1 ^7 ^6 ^4 ^4 ^3 ^1 ^2 ^1
w:sol me do te le fa fa me do re do{% endcapture %}
{% include abc-example.html number="2" abc=ex2

### Harmonic minor

{% capture ex3 %}X:3
T:Happy Birthday in E harmonic minor
T:using the relative minor to G major
M:3/4
L:1/4
Q:1/4=90
K:G
B,/2>B,/2| C B, E| ^D2 B,/2>B,/2| C B, F| E2 B,/2>B,/2|
w:^5 ^5 ^6 ^5 ^1 ^#7 ^5 ^5 ^6 ^5 ^2 ^1 ^5 ^5
w:sol sol le sol do ti sol sol le sol re do sol sol
B G E| ^D C A/2>A/2| G E F| E2|]
w:^5 ^3 ^1 ^#7 ^6 ^4 ^4 ^3 ^1 ^2 ^1
w:sol me do ti le fa fa me do re do{% endcapture %}
{% include abc-example.html number="3" abc=ex3

### Melodic minor

Note: When first determining your basic rules for melodic minor, you may want to choose to ignore 'le' in measure 6. That pitch is serving a harmonic goal at that moment as part of a *cadence*, rather than a melodic function.

{% capture ex4 %}X:4
T:Happy Birthday in G melodic minor
T:using the relative minor to G major
M:3/4
L:1/4
Q:1/4=90
K:Bb
D/2>D/2| E D G| ^F2 D/2>D/2| E D A| G2 D/2>D/2|
w:^5 ^5 ^6 ^5 ^1 ^#7 ^5 ^5 ^6 ^5 ^2 ^1 ^5 ^5
w:sol sol le sol do ti sol sol le sol re do sol sol
d B G| F HE c/2>c/2| B G A/4D/4=E/4^F/4| G2|]
w:^5 ^3 ^1 ^7 ^6 ^4 ^4 ^3 ^1 ^2 ^5 ^#6 ^#7 ^1
w:sol me do te le fa fa me do re sol la ti do{% endcapture %}
{% include abc-example.html number="4" abc=ex4

### Major pentatonic

This is more of a teaching example rather than an actual conversion, because the major scale and major pentatonic scales do not share the same type of relationship that major and minor do.

{% capture ex5 %}X:5
T:Happy Birthday in G major pentatonic
M:3/4
L:1/4
Q:1/4=90
K:G
D/2>D/2| E D G| D2 D/2>D/2| E D A| G2 D/2>D/2|
w:^5 ^5 ^6 ^5 ^1 ^6 ^5 ^5 ^6 ^5 ^2 ^1 ^5 ^5
w:sol sol la sol do sol sol sol la sol re do sol sol
d B G| D E d/2>d/2| B G A| G2|]
w:^5 ^3 ^1 ^5 ^6 ^5 ^5 ^3 ^1 ^2 ^1
w:sol mi do sol la sol sol mi do re do{% endcapture %}
{% include abc-example.html number="5" abc=ex5

### Minor pentatonic

The same can be stipulation applies to the minor pentatonic scale that applied to the major pentatonic scale. These scales do not correlate to their seven-note counterparts in the same manor that the major and minor scales do.

{% capture ex6 %}X:6
T:Happy Birthday in G minor pentatonic
M:3/4
L:1/4
Q:1/4=75
K:Bb
D/2>D/2| F D G| D2 D/2>D/2| F D B| G2 D/2>D/2|
w:^5 ^5 ^7 ^5 ^1 ^5 ^5 ^5 ^7 ^5 ^3 ^1 ^5 ^5
w:sol sol te sol do sol sol sol te sol me do sol sol
d c B| G HF c/2>c/2| B G F| G2|]
w:^5 ^4 ^3 ^1 ^7 ^4 ^4 ^3 ^1 ^7 ^1
w:sol fa me do te fa fa me do te do{% endcapture %}
{% include abc-example.html number="6" abc=ex6