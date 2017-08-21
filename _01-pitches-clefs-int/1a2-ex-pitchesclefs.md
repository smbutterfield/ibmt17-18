---
layout: page
title: 1a Examples - Pitches and Clefs
abc: true
---

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