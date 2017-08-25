---
layout: chapter
title: 1c Examples - Identifying and Labeling Intervals
abc: true
---

In the example below, each interval represents the concept stated at the beginning of its staff, but each measure also has an important intervallic relationship to the measures above and below it.

### Important concepts

*Qualities*: P = perfect, M = major, m = minor, A = augmented, d = diminished

*Diatonic intervals in the examples below*
- Major 3rd from the harmonic intervals
- Major 2nd from the melodic intervals
- Major 6th from simple intervals
- Perfect 15th and major 10th from the compound intervals
- Minor 6th from the inversion pairs

*Chromatic intervals in the examples below*
- All other intervals

{% capture ex1 %}X:1
T:Intervals
M:1/4
L:1/4
K:C
V:1 name=Harmonic
[_e_B]| [_BA]| [^f^F]| [D_A]| [_d^F]| [ce]||
w: P4 m2 P8 d5 d6 M3
V:2 name=Melodic
e/2_B/2| B/2A/2| f/2^F/2| _D/2_A/2| F/2_d/2| c/2^e/2||
w: A4 _ M2 _ d8 _ P5 _ m6 _ A3
V:3 name=Simple
[_eB]| [__BA]| [^fF]| D/2^A/2| F/2d/2| [c_e]||
w: d4 d2 A8 A5 _ M6 _ m3
V:4 name=Compound clef=bass
[_E_B,,]| [_B,A,,]| [FF,,]| _A,/2D,,/2| F,,/2_D/2| [C,E]||
w: P11 m9 P15 d5 _ m13 _ M10||
V:5 name=Inversions
[_E_B]| [_B,A]| [^f^F]| [d_A]| [_df]| [cE]||
w: P5 M7 P1 A4 M3 m6{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}