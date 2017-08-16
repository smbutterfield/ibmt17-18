---
layout: page
title: 1b Examples - Labeling Pitches
abc: true
---

## Accidentals and Enharmonic Equivalence

{% include abc-example.html number="1" abc='X:1
T: Enharmonic Equivalence
T: Each measure contains two notes that are enharmonically equivalent.
M:2/2
L:1/2
K:C
V:1 name="Treble Clef"
_B ^A |f ^e |^^E ^F |]
V:2 name="Alto Clef" clef="alto"
^G _A |B, _C |^^G, A,|]
V:3 name="Tenor Clef" clef="tenor"
^F, _G, |F, _E, |D, ^^C,|]
V:4 name="Bass Clef" clef="bass"
_D, ^C, |^B,, C, |D, ^^E,|]' %}

## Labeling Octaves and Clef Relationships

{% include abc-example.html number="2" abc='X:1
T: Pitches and Clefs
M:2/2
L:1/2
K:C
V:1 name="Treble Clef"
e a f b g ^c B|]
w: E5 A5 F5 B5 G5 C#5 B4
V:2 name="Alto Clef" clef="alto"
E A F B G ^C B,|]
w: E4 A4 F4 B4 G4 C#4 B3
V:3 name="Tenor Clef" clef="tenor"
E, A, F, B, G, ^C, B,,|]
w: E3 A3 F3 B3 G3 C#3 B2
V:4 name="Bass Clef" clef="bass"
E, A, F, B, G, ^C, B,,|]
w: E3 A3 F3 B3 G3 C#3 B2' %}