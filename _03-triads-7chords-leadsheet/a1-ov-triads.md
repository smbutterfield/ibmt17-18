---
layout: chapter
title: Overview 3a - Triads
abc: true
---

When we discussed how key signatures function, we explored the idea that the perfect 5th for dividing the octave into twelve parts. By inserting a non-perfect 5th into the string of perfect 5ths, we found the critical change from which diatonic functions arise. 

The effect of this change can be seen easily when looking at the naturally ocurring 5ths stacked on a major scale.

{% capture ex1 %}X:1
%%staffsep 100%
T:Diatonic 5ths in the Major Scale
M:C
L:1/2
K:C
[CG] [DA]| [EB] [Fc]| [Gd] [Ae]| [Bf] [cg]||
w:P5 P5 P5 P5 P5 P5 d5 P5{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

If you study the evolution of music, you will find that harmony remained focused on perfect intervals for a long time, but the next big revolution came as composers began dividing the perfect 5th in half and adding a third chord member. This "chordal third" created two stacked intervals of a 3rd which we now call a *triad*. It is because of these thirds that we call any triadic-based music *tertian harmony*.

{% capture ex2 %}X:2
%%staffsep 100%
T:Diatonic triads in the Major Scale
M:C
L:1/2
K:C
[CEG] [DFA]| [EGB] [FAc]| [GBd] [Ace]| [Bdf] [ceg]||
w:M m m M M m d{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

Triads are important to almost all of Western music and form the basic unit in diatonic (key-based) harmony. While many systems have evolved to describe how they *function* harmonically, we must first be able to classify and label them in an objective manner. This means that we cannot rely on key-based functions right away; instead, we can classify them using their intervallic structure.

As dyads have two pitches, all triads have exactly three pitches, although certain chord members can occasionally be omitted (and therefore implied) depending on the context. We name the chord members by the distance above the bottom pitch **when the chord is stacked in thirds**:
- the lowest pitch is called the *root* of the chord
- the pitch that is a 3rd above the root is called the *chordal third*
- the pitch that is a 5th above the root is called the *chordal fifth*

This can be confusing to theory students, because we refer to intervals as chordal members using the same words -- thirds and fifths -- and most often do not use the word "chordal". As you become more experienced in describing these things, you will be able to discern the meaning from context, but if you would like to avoid confusion for now, you can preface the ordinal number with the word "chordal" until you are comfortable. 

Because there are three pitches, there are three possible configurations that depend on which note of the triad is in the lowest voice. We will call these *inversions*, but they are sometimes referred to as *positions*. The system that we use to label inversions relies on the intervals within the triad.