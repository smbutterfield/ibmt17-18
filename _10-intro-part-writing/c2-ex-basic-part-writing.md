---
layout: chapter
title: Examples 10c - Error detection
abc: true
---

Create longer part-writing example with errors at top.

{% capture ex1 %}X:1
T:Parallel perfect octaves (PP8)
M:4/4
L:1/2
K:C
V:1
[cE] [AD]| [BF] [cE]|]
V:2 clef=bass
[C,G,] [F,A,] | [B,G,] [C,C]|]
w:C:I ii6 V7 I{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

Follow the following steps to identify errors:

1. *Voice-crossing*
    - Exception: alto and tenor may cross briefly if musically necessary
2. *Spacing*: In a four-part texture, are the top three voices within an octave of the adjacent voices?
3. *Range*
4. *Doubling* 
5. *Similar 5ths and 8ves*
    - Follow the soprano line looking for leaps
    - When a leap is found, look to see if there is similar motion in the bass (not parallel)
    - Determine the interval between the outer voices of the second chord. - If this interval is either a P5 or P8, there is a similar 5th or 8ve.
6. *Parallel Perfect 5ths and 8ves*
    - Determine the interval between each pitch horizontally (melodically -- NOT within each chord (vertically)
    - If one of the new vertical stacks of four intervals (numbers only) contains two matching numbers, check to see if the intervals within each chord (vertically) are P5s or P8s.
      - With triads, P5s must always have the root of the chord on the bottom of a major or minor chord. No other combination or chord can produce a P5.
       - P8s must come from doubled voices moving to doubled voices
    - If there are two consecutive P5s or P8s, those are parallel 5ths or 8ves.
7. *Unacceptable Unequal 5ths*
    - Should be found while looking for parallel 5ths using same method as above.
    - When completing step 2, if a d5 moves to a P5 and it involves the bass line, this is unacceptable unequal 5ths
8. *Contrary Perfect 5th and 8ves*
    - After completing step 1 of the parallel 5ths/8ves instructions, look for inverted pairs of numbers (e.g. 2 and 7, 3 and 6, 4 and 5) within each number stack
    - If one of the new vertical stacks contains one of these inversion pairs, check to see if the intervals within each chord (vertically) are P5s or P8s.
    - With triads, P5s must always have the root of the chord on the bottom of a major or minor chord. No other combination or chord can produce a P5.
    - P8s must come from doubled voices moving to doubled voices
    - If there are two consecutive P5s or P8s, those are contrary 5ths or 8ves.
