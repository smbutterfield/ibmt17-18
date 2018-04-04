---
layout: chapter
title: 23b Examples - PC Set Inversion
abc: true
---

Transposition is the most commonly used set manipulation, but there is a second commonly used function that is of equal importance to understanding pc sets.

## Inversion

When first studying tonal harmony, we discussed the scale degree names in pairs: dominant/subdominant, mediant/submediant, subtonic/supertonic. For each of these pairs, there is a duality to their naming in that they share a relationship centered around the tonic pitch. For example, the dominant is a P5 *above* the tonic where the subdominant is a P5 *below* the tonic. They are mirrored around the central pitch, and therefore represent an *inversion* of each other.

In set theory, we can perform this same operation using intervals (i.e. numbers of half-steps). Take a moment to think about how to translate the concept of inversion from traditional intervals (e.g. P5,M3) into pitch-class integers. What kind of results do you expect for integer notation? Remember that to find an inversion of any musical pitch, you need two pieces of information: the starting pitch class and the pitch class *around* which you will invert. 

## Visually inverting pitch classes

Depending on the central pitch used to invert, pitch-class integer notation can make inversion relatively easy. It does not require you to understand a specialized pitch and interval system like traditional notation. Instead, it only requires basic mathematical functions. 

Before tackling the mathematical approach to inverting pitch-class integers, let's visually explore inversion using the pitch class continuum below. For simplicity's sake, let's start by centering our inversions around C/0. To visually find an inversion, pick a letter/integer on the chart below. Count the number of steps it takes to reach C/0, and then continue past C/0 for the same number of steps. (You can think of it as balancing the scale.) Create a chart showing all inversion pairs in **both** pitch letter notation and pitch-class integer notation. What is the inversion for C/0? Why?

-e | -t | -9 | -8 | -7 | -6 | -5 | -4 | -3 | -2 | -1 | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | t | e
 --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | ---
 C# | D | D# | E | F | F# | G | G# | A | A# | B | C |  C# | D | D# | E | F | F# | G | G# | A | A# | B

Your first chart should have 12 pc sets, although two of them are technically only one pitch name -- C/0 and F#/6 end up inverting on top of themselves meaning that they are monads. However, as you look at the pairs, do you see a pattern? How many *unique* pc sets are there if you only look at pitch letter names?

## Applying Mod12

As you hopefully can see, there are only six *unique* inversion pairs when you eliminate duplicates when looking at the pitch letters. However, when we instead look at the pitch-class integers, you still have 12 unique pc sets because negative numbers differentiate the sets. You have just demonstrated the importance of using Mod12 to simplify all pc sets to only include integers between 0 and 11. (This is also a visual demonstration of how *octave equivalency* works.) If you look at the chart below, you can see what happens when we apply Mod12 to a series of integers; it creates a continuously repeating set of integers between 0 and 11, which means that you inversion is simple when using fixed zero.

-e | -t | -9 | -8 | -7 | -6 | -5 | -4 | -3 | -2 | -1 | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | t | e
 --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | ---
 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | t | e | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | t | e

 This means that the inversion pairs when inverting around zero (and 6) are:

 Inversion Pair 1 | Inversion Pair 2
 --- | ---
 0 | 0
 1 | e
 2 | t
 3 | 9
 4 | 8
 5 | 7
 6 | 6

Another method for teaching inversion uses the visual aid of a clock to show inversion. First, draw a clock (with 0 in the place of 12). Then draw a line between opposite sides of the clock; this line will represent your inversion center, so to invert around 0, your line should connect 0 and 6. Use this line as a mirror to find your inversion pairs by looking at what is directly across the line, and you will see that you create the same set of inversion pairs above. If you were to move your line to connect a different set of opposites, say 2 and 8, what would this represent?

## Solving inversions mathematically

As with transposition, we have shorthand to represent inversion. To show the inversions around zero used to create the chart above we would write:

T<sub>0</sub>I (0,1,2,3,4,5,6) = (0,e,t,9,8,7,6)

If you then put the result in normal form you would get (6,7,8,9,t,e,0).

What if you wanted to invert *and* transpose a pc set? Try inverting and transposing the following pc set, but do it two different ways to see if you get the same results:
- Transpose first, then invert
- Invert first, then transpose

T<sub>4</sub>I(1,5,6)

Did you get the same result either way? If not, why are the different? Which do you think is correct? Why?

## The shortcut

Inverting first will always give you the correct answer, because in that case you are inverting *around zero* and then transposing. If you transpose first, you are actually inverting around a differnent axis.

Luckily there is a mathematical shortcut for inverting around zero and transposing. Look at the following correctly solved examples. Do you see a relationship between the formula and answers?

