---
layout: chapter
title: 23a Examples - Basic PC Set Manipulation
abc: true
---

In Unit 22, we introduced *integer notation* for *pitch classes*. Allen Forte first formalized this system in his seminal work, *The Structure of Atonal Music*, because standard analytical methods do not work when the music leaves traditional tonality. His *set theory* is a specialized form of analysis that looks for intervallic patterns equally across all twelve chromatic pitches, rather than focusing on the relationship between a central pitch (i.e. tonic) and the other pitches. 

## Scratching the surface

*Set theory* is a deep field of theoretical study, and we will only introduce a few basic concepts in this unit. If you would like to explore this topic further -- and if you intend to go beyond the undergraduate level of music study, you should -- I highly recommend that you read the some of the many fine textbooks written on the subject. My favorites include:
- *The Structure of Atonal Music* - Allen Forte
- *Introduction to Post-tonal Theory* - Joseph Straus
- *Basic Atonal Theory* - John Rahn

There have been numerous refinements and alterations to this method since the first publication of Forte's text in 1973, so this unit will attempt to distill the basics that I have found most useful in understanding how these methods approach analysis.

## Notating pitch-class sets

When we introduced pc sets in Unit 22, we did not formalize their notation, however, because we will study various levels of organization within pc sets, it is important to establish a standard form for writing an unordered pc set. When writing a pc set that you have not specifically organized, you should always notate this using parentheses with a comma between each pitch class. The following are all examples of unordered pc sets:

- (0,1,5,t)
- (B-flat,C,D,G)
- (2,4)
- (0,1,3,5,6,7,8,9,e)
- (B,C,D,E,F,G,A)

## Modulo 12 arithmetic

Before we begin using integer notation to study pitch classes and pitch-class sets, we must establish the mathematical method necessary for manipulating pitches. Because music uses twelve equally-spaced pitches but our standard counting system is based around tens, we must create a specific equivalency around the number 12. For this, we use modulo 12 (mod12) arithmetic. You already use modulo 12 arithmetic every time you count time in hours, assuming that you use a 12-hour system. For example, if it is 11:00 and you have a meeting in three hours, what time is your meeting? From experience, you understand that when you reach 12, you must reset your counting to find the meeting's start time at 2:00 -- not 14:00. (Again, this assumes that you are not using a 12-hour clock cycle, not 24-hour.)

This is exactly how pitch-class integer notation works, although the system begins numbering on 0 instead of 12. In this system, each time you pass 11, you begin again at zero, therefore making every multiple of 12 equal to zero. Complete the following chart to show the first two equivalencies for every number in this system. Can you create a method to quickly find any level of equivalency?

Pitch-class integer | First equivalency | Second equivalency
 --- | --- | ---
 0 | 12 | 24
 1 | 13 | 25
 2 | 14 | --
 3 | -- | --
 4 | -- | --
 5 | -- | --
 6 | -- | --
 7 | -- | 31
 8 | -- | --
 9 | -- | --
 t (10) | -- | --
 e (11) | 23 | --

## Transposition using integer notation

Fixed-zero integer notation assigns the following integers to pitch-classes:

 Pitch-class integer | Pitch 1 | Pitch 2
 --- | --- | ---
 0 | C | B-sharp
 1 | C-sharp | D-flat
 2 | D | --
 3 | D-sharp | E-flat
 4 | E | F-flat
 5 | F | E-sharp
 6 | F-sharp | G-flat
 7 | G | --
 8 | G-sharp | A-flat
 9 | A | --
 t (10) | A-sharp | B-flat
 e (11) | B | C-flat

This is relatively simple to memorize, but it is more important to consider what these numbers truly represent. Consider the following pitch-class set:

`(E, F, G, B-flat)`

First, transpose these pitches up a P4, and as you do this, pay careful attention to the method that you use for transposing. Do you think of each pitch as part of a key? If so, what scale degree do you use for each pitch? Do you count half-steps? Do you find the first pitch and then as the base for finding the rest of the intervals?

Next:
- Convert this pitch-class set into integer notation
- Then add 5 to each number
- For any resulting number greater that 11, convert that number to its lowest possible integer using mod12 from above. 
    - For example, if you were to get 13, you would need to subtract 12 to get 1.
- Convert this new set of integers into pitch letter names. 

Did you get the same result as when you transposed the pitches using the traditional method for pitch transposition? If so, why does this work? What do the numbers for integer notation *actually* represent? (Hint: it is not the assigned pitches.)

## Notating transposition

Hopefully, you came to the same result using both methods of transposition. The pc set becomes (4,5,7,t), and then when you add 5 to each integer it becomes (9,t,12,15). All numbers greater than 11 must be reduced by mod12, so the set becomes (9,t,0,3). When these numbers are converted back into pitch letter names, you get (A,B-flat,C,E-flat) which is exactly a P4 above the original pc set.

This works, of course, because the numbers in integer notation are actually representing the number of half-steps above a given pitch. When using fixed zero, each integer represents that many half-steps above C. From this, we derive the following chart, although if you have already memorized the integers for fixed-zero notation, you can always "reverse engineer" this chart using your knowledge of intervals within the C major scale.

 Pitch-class integer | Interval 1 | Interval 2 | Interval 3
 --- | --- | --- | ---
 0 | unison | d2 | A7
 1 | m2 | (augmented unison) | --
 2 | M2 | d3 | --
 3 | m3 | A2 | --
 4 | M3 | d4 | --
 5 | P4 | A3 | --
 6 | A4 | d5 | --
 7 | P5 | d6 | --
 8 | m6 | A5 | --
 9 | M6 | d7 | --
 t (10) | m7 | A6 | --
 e (11) | M7 | (diminished unison) | --

 When notating transposition, we write T<sub>n</sub> where n = the interval by which you will transpose. The example above would be notated:

 T<sub>5</sub>(E, F, G, B-flat) = (A,B-flat,C,E-flat)

 OR using integer notation
 
 T<sub>5</sub>(4,5,7,t) = (9,t,0,3)

## Transposing downward

Any positive integer implies a transposition upward, but a negative integer can be used to transpose downward. For example, perform the following transposition:

T<sub>-3</sub>(4,5,7,t)

This example is simple enough because each of the integers is easily reduced by -3 to create (1,2,4,7). However, try the following:

T<sub>-5</sub>(4,5,7,t)

In this example, 4 - 5 = -1. What does -1 equal? Because we use mod12, you can simply add 12 to this number to find its simplest equivalency.

-1 + 12 = 11

Just as you must reduce any number greater that 11 to an integer between 0 and 11, you must also increase any number less than 0. Therefore the set above is:

T<sub>-5</sub>(4,5,7,t) = (e,0,2,5)

## Normal form

In order to make comparing pc sets more useful, we need to use standardized orders to create consistent comparisons. You can imagine how difficult it would be to make sense of a series of pc sets if each set was in a random order. For this, we use *normal form*.

Normal form is similar to the way in which we analyze standard tonal harmony. For example, how would you condense the following open voicing of a seventh chord in its simplest form while retaining its inversion?

{% capture ex1 %}X: 1
T:C major seven
M:4/4
L:1
K:C
V:1
[BG]|]
V:2 clef=bass
[E,C]|]{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

Most people will reduce this to a closed-position chord such as the following, because it shows every pitch and the inversion, but it does it in the smallest space possible. This makes it easy to see the intervals and construction of the chord:

{% capture ex2 %}X: 2
T:C major seven
M:4/4
L:1
K:C
V:1
[EBGc]|]{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

*Normal order* follows the same principles for pc sets. For example, take the following pc set and arrange it so it fill the smallest space possible. Or to put it more precisely, you must find the ascending arrangement that has the smallest interval between the outside pitch classes. You may use any method that works, but common methods include using mod12, notating the pitches on a staff, or even drawing the pitches on a clock face. As you work through, consider the speed and efficacy of each method that you try.

(1,7,t)

For this trichord, it is probably easiest to translate the pitches into standard pitch letters, and then just treat it as a triad. In this case, the pitches D-flat, G, and B-flat form a G diminished triad, so you can quickly tell that the normal form for this should be:

[7,t,1]

Notice that when notating a pc set in normal form, the parentheses are replaced by brackets. (This notation method is outlined by Joseph Straus in his *Introduction to Post-Tonal Theory*.)

But what happens when you have a more complicated and ambiguous pc set? Try putting the next pentachord into normal form. What difficulties do you find? Which method seems to get the quickest result? Which seems the most consistent?

(1,3,7,t)

## When there are "ties" for normal form

With any pc set, it is possible that there are multiple arrangements that have the same interval between the outside pitches. Try putting the following trichord into normal form.

(0,5,7)

If you arrange this on a staff in all possible ascending orders, you get:

{% capture ex3 %}X: 3
T:Three possible arrangements of (0,5,7)
M:4/4
L:1
K:C
V:1
[CFG]| [FGc]| [Gcf]|]{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

From this, it is obvious that you can eliminate the last arrangement, but how do you choose between the first two which both have an outer interval of 7 (P5)? In this case, we go to the first tie-breaker of looking at the distance between the lowest pitch and the second highest pitch. In the above example, the second interval for the first arrangement is 5 (P4), but the second interval for the second arrangement is only 2(M2). In this case the normal form this trichord is [0,2,7].

Try using this on a more difficult example. The following pentachord has multiple ties and will require you to work through multiple levels. Remember that each tie is broken by measuring the first pitch against the next closest pitch. While working through this, how many permutations in ascending order are there for a this set? How does that number relate to the cardinality for any set?

(2,3,5,8,e)