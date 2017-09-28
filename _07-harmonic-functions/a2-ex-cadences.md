---
layout: chapter
title: Examples 7a - Cadences
abc: true
---

{% capture ex1 %}X:1
T:Standard cadences
T:Old hundredth psalm
M:4/4
L:1/4
Q:1/4=80
K:G
V:1
[GD]| [GD] [FD] [EB,] [DD]| [GB,] [AD] H[BD]
[BD]| [BD] [BG] [AF] [GG]| [cG] [BG] H[AF]
[GG]| [AF] [GB] [AF] [DG]| [EE] [FD] H[GD]
[dD]| [BD] [GG] [AF] [cA]| [GB] [AF] H[GG]|]
V:2 clef=bass
[G,B,]| [G,B,] [A,D,] [E,G,] [B,,G,]| [E,G,] [D,F,] H[G,G,,]
w: _ _ _ _ _ _ _ HC
[G,G,]| [G,G,] [G,D] [DD,] [E,B,]| [C,E] [G,,D] H[DD,]
w:  _ _ _ _ _ _ _ IAC
[E,B,]| [D,D] [G,D] [D,D] [B,,G]| [C,G,] [D,C] H[B,G,,]
w: _ _ _ _ _ _ _ DC
[G,B,]| [G,G,] [E,B,] [D,D] [A,,E]| [D/2B,,/2]-[D/2C,/2] [D/2D,/2]-[C/2D,/2] H[G,,B,]|]
w: _ _ _ _ _ _ _ PAC{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

{% capture ex2 %}X:2
T:Phrygian cadence
M:4/4
L:1
K:C
V:1
c| B| A| e| d| c| F| G| B| c|]
w:P8 M6 M3 M3 m3 P8 m6 m3 M6 P8
c| B| c| F| G| A| f| e| c| B| c|]
w:P8 M6 P5 m3 m3 M6 m3 P8 m6 M6 P8
c| d| c| d| A| B| d| f| e| d| c|]
w:P8 m3 m6 P8 M3 M3 M6 m3 M3 m3(m10) P8
c| g| f| c| d| a| g| d| e| B| c|]
w:P8 m3 m6 P8 P5 M3 M6 m6 M3 M6 P8
V:2
C,| D,| F,| C| B,| C| A,| E| D| C|]
C,| D,| F,| D,| E,| C,| D,| E,| E| D| C|]
C,| B,,| E,| D,| F,| G,| F,| D,| C,| B,,| C,|]
C,| E,| F,| A,| G,| F,| G,| F,| E,| D,| C,|]{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}