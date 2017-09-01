---
layout: chapter
title: Examples 1b - Labeling Pitches
abc: true
---

## Goals for this topic

Using the examples below, determine:
- three *enharmonic equivalents* for every *pitch-class*
    - one *pitch-class* only has two enharmonic equivalents if only using the five most common accidentals
- where C4 lies in each clef
- what the numeral refers to in the ISO system for labeling octaves
- how these numerals interact with letters

## Accidentals and Enharmonic Equivalence

{% capture ex1 %}X:1
T:Enharmonic Equivalence
T:Each measure contains two notes that are enharmonically equivalent.
M:2/4
L:1/4
K:C
V:1 name="Treble Clef"
_B ^A |f ^e |^^E ^F |]
V:2 name="Alto Clef" clef="alto"
^G _A |B, _C |^^G, A,|]
V:3 name="Tenor Clef" clef="tenor"
^F, _G, |F, ^E, |D, ^^C,|]
V:4 name="Bass Clef" clef="bass"
_D, ^C, |^B,, C, |D, __E,|]{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

## Labeling Octaves and Clef Relationships

{% capture ex2 %}X:2
T:Pitches and Clefs
M:C
L:1/4
K:C
V:1 name="Treble Clef"
e a f b g ^c B|]
w: E5 A5 F5 B5 G5 C#5 B4
V:2 name="Alto Clef" clef=alto
E A F B G ^C B,|]
w: E4 A4 F4 B4 G4 C#4 B3
V:3 name="Tenor Clef" clef=tenor
E, A, F, B, G, ^C, B,,|]
w: E3 A3 F3 B3 G3 C#3 B2
V:4 name="Bass Clef" clef=bass
E, A, F, B, G, ^C, B,,|]
w: E3 A3 F3 B3 G3 C#3 B2{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}
