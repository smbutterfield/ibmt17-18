---
layout: page
title: 1c Examples - Identifying and Labeling Intervals
---

## Intervals

{% capture ex1 %}X:1
T:Intervals
T:P = perfect, M = major, m = minor, A = augmented, d = diminished
M:1/4
L:1/4
K:C
V:1 name="Harmonic Intervals"
[_e _B]| [_B A]| [^f ^F]| [D_A]| [_d^F]| [c e]||
w: P4 m2 P8 d5 d6 M3
V:2 name="Melodic Intervals"
e/2_B/2| B/2A/2| f/2^F/2| _D/2_A/2| F/2_d/2| c/2^e/2||
w: A4 _ M2 _ d8 _ P5 _ m6 _ A3
V:3 name="Simple Intervals"
[_e B]| [__B A]| [^f F]| D/2^A/2| F/2d/2| [c _e]||
w: d4 d2 A8 A5 _ M6 _ m3
V:4 name="Compound Intervals" clef=bass
[_E _B,,]| [_B, A,,]| [F F,,]| _A,/2D,,/2| F,,/2_D/2| [C, E]||
w: P11 m11 P15 d5 _ m13 _ M10||
V:5 name="Inversion Pairs"
[_E _B]| [_B, A]| [^F ^F]| [d_A]| [_df]| [c E]||
w: P5 M7 P1 A4 M3 m6"{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}