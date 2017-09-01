---
layout: chapter
title: Examples 1a - Pitches and Clefs
abc: true
---
## Goals for this topic

Use the examples below to find:
- the order of pitch names for each clef's lines and spaces.
- why treble clef is a G-clef, why bass clef is an F-clef, and why alto and tenor clefs are C-clefs.
- any tips or tricks that may help in differentiating and reading clefs.
    - Hint: Many students begin their studies of clefs by relating the unfamiliar clefs to their most familiar clef.

{% capture ex1 %}X: 1
T: Pitches and Clefs
M: 4/4
L:1/4
K:C
V:1 name="Treble Clef"
e a f b g ^c G|]
w: E A F B G C# G
V:2 name="Alto Clef" clef="alto"
E A F B G ^C G,|]
w: E A F B G C# G
V:3 name="Tenor Clef" clef="tenor"
E, A, F, B, G, ^C, G,,|]
w: E A F B G C# G
V:4 name="Bass Clef" clef="bass"
E, A, F, B, G, ^C, G,,|]
w: E A F B G C# G{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}