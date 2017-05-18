---
layout: post
title: Using Trinket
---

<iframe class="trinket" src="https://trinket.io/embed/music/a089e987ca" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe><br/>
*Error-detection exercise from [Composing a first-species counterpoint](http://openmusictheory.com/firstSpecies.html).*

[Trinket](http://trinket.io) is a new tool for interactive music notation on the web. It can be added to any website that supports iFrames, and there are several music trinkets embedded in Open Music Theory (with more on the way as the textbook grows).

## Notation guide

Music notation is created by entering text into a box at the bottom of the trinket. Trinkets offer a limited set of musical features, in order to keep things simple. The text required for these features is provided below. Most of these features are included in the example trinket at the bottom of this page.

### Pitch

Pitch classes are designated by their letter names followed by - for flat, # for sharp, or "n" for natural. Rests are designated by "r".

In order to avoid confusion with rhythmic numbers, trinket uses a version of the Helmholtz register designation. So ISO Octave 4 (middle C up to the B above it) uses lower case letters:

    c d e f g a b

<br/>
ISO Octave 5 adds primes:

    c' d' e' f' g' a' b'

<br/>
ISO Octave 6 takes two primes (c''), Octave 7 three primes (c'''), etc.

Octave 3 (immediately below middle C) uses capital letters:

    C D E F G A B
	
<br/>
Octave 2 uses two capital letters:

    CC DD EE FF GG AA BB

<br/>
And so on.

### Rhythm

Rhythms are designated by numbers representing note values—2 for half note, 4 for quarter note, etc.—and periods for dotted notes—2. for dotted half note, 4.. for doubly dotted quarter note, etc. These numbers immediately follow the pitches.

Ties are denoted by placing a ~ immediately after the rhythmic value.

### Chords

To make a chord, simply put two or more notes within angled brackets (and put the rhythm outside the bracket).

    <c e g>4. <d f>8

<br/>

### Lyrics

When using lyrics, simple type lyrics (or analytical notation) into the lyric box. Use a space to move on to the next note. When skipping a note, put a ~ for the notes that don't take lyrics.

### Example

Here is an example that uses many of the features listed above. (International readers, please forgive the movable-do!)

<iframe src="https://trinket.io/embed/music/91c673df7c" width="100%" height="260" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe><br/>