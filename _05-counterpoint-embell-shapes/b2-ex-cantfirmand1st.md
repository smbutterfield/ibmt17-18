---
layout: chapter
title: Examples 5b - Cantus Firmus and 1:1 Counterpoint
abc: true
---

Use the following examples of first-species (1:1) counterpoint to develop guidelines for writing in this style. Generally these rules can be broken into three categories:
- Rules about *constructing a melodic line*
    - Length
    - Starting and ending pitches
    - Approaching the final note
    - Repeated pitches
    - Melodic intervals
        - Leaps
        - Resolutions following leaps
    - Range
    - Climax (position in melody and frequency)
- Rules regarding acceptable *intervals* between lines
    - Valid harmonic intervals
    - Approaching perfect intervals
    - Number of times that an interval can be used consecutively
- Rules regarding acceptable *motion* between lines
    - Acceptable types of motion

**Note that these examples are taken from a counterpoint random generator and lack some of the elegance that human-composed counterpoint tends to have.**

{% capture ex1 %}X:1
T:First species (1:1) examples.
T:Each system is a new example.
M:4/4
L:1
K:C
V:1 name=CP1
c| B| A| e| d| c| F| G| B| c|]
w:P8 M6 M3 M3 m3 P8 m6 m3 M6 P8
c| B| d| f| e| A| B| G| c| B| c|]
w:P8 M6 M6 m3 P8 M6 M6 m3 m6 M6 P8
c| B| A| F| G| A| f| e| c| B| c|]
w:P8 M6 M3 M3 m3 P8 m6 m3 M6 P8
c| d| c| d| A| B| d| f| A| B| c|]
w:P8 m3 m6 P8 M3 M3 M6 m6 M3 M6 P8
c| g| f| c| d| a| g| d| e| B| c|]
w:P8 m3 m6 P8 M3 M3 M6 m6 M3 M6 P8
V:2 clef=bass name=CF
C,| D,| F,| C| B,| C| A,| E| D| C|]
C,| D,| F,| D,| E,| C,| D,| E,| E| D| C|]
C,| D,| F,| D,| E,| C,| D,| E,| E| D| C|]
C,| B,,| E,| D,| F,| G,| F,| A,| F,| D,| C,|]
C,| E,| F,| A,| G,| F,| G,| F,| E,| D,| C,|]{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}