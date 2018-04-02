---
layout: chapter
title: 23a Lesson - Basic PC Set Manipulation
abc: true
---

# Class discussion



# Further reading

## From *Open Music Theory*

### Transposition

In post-tonal music, transposition is often associated with motion: Take a chord, motive, melody, and when it is transposed, the aural effect is of *moving* that chord, motive, or melody in some direction. That’s the effect here, in two disconnected passages from Debussy's, *La cathédrale engloutie*:

[![](/images/postTonal/transposition.png)](/images/postTonal/transposition.png)

The opening motive — comprising the notes B, D, E, or {11, 2, 4} — is transposed four semitones higher in m. 18, representing the cathedral’s slow ascent above the water. Transposing something preserves its intervallic content, and not only that, it preserves the specific arrangement of that thing’s intervals. When we hear the passage at m. 18 above, we recognize its relationship to the passage in m. 1 because the same intervals return, but starting on a different pitch.

Transposition is an operation — something that is *done* to a pitch, pitch class, or collection of these things — or alternatively a *measurement* — representing the distance between things. We represent it as *Tn*, where *n* represents the ordered pitch-class interval between the two things. To transpose something by *Tn*, add *n* to every element in that thing (mod 12). Given the collection of pitch classes in m. 1 above and transposition by *T4*:

[![](/images/postTonal/t4.png)](/images/postTonal/t4.png)

The result is the pitch classes in m. 18. *T4* {11, 2, 4} = {3, 6, 8}.

Alternatively, to determine the transpositional relationship *between* two things, subtract the first thing from the second. If the numbers that result are all the same, the two things are related by that *Tn*.

[![](/images/postTonal/t4Measurement.png)](/images/postTonal/t4Measurement.png)

This is how I arrived at the *T4* arrow label in the musical example above, by “subtracting” the pitch class integers of m. 1 from the pitch-class integers in m. 18.

### Normal Form

Normal order (sometimes called normal form) has a lot in common with the concept of triad “root position.” Among other things, root position is a standard way to order the pitch-classes of triads and seventh chords so that we can classify and compare them easily. Normal order does the same, but in a more generalized way so as to apply to chords containing a variety of notes and intervals.

Normal order is the most compressed way to write a given collection of pitch classes. Often, you’ll be able to determine normal order intuitively using a keyboard or a clockface, but it’s good to learn a process that will always give you the correct answer.

1. Write as a collection of pitch classes (eliminating duplicates) in ascending order and within a single octave. There are many possible answers.
2. Duplicate the first pitch class at the end. 
3. Find the largest ordered pitch-class interval between adjacent pitch classes.
4. Rewrite the collection beginning with the pitch class to the right of the largest interval and write your answer in square brackets.

For example, given {G-sharp4, A2, D-sharp3, A4}:

1. *Write as a collection of pitch classes (eliminating duplicates) in ascending order and within a single octave.* {8,9,3}
2. *Duplicate the first pitch class at the end.* {8,9,3,8}
3. *Find the largest ordered pitch-class interval between adjacent pitch classes.* In this case, the largest interval is between "9" and "3."
4. *Rewrite the collection beginning with the pitch class to the right of the largest interval and write your answer in square brackets.* [3,8,9]

Occasionally you’ll have a tie in step 3. In these cases, write the ordering implied by each tie and calculate the interval from the first to the penultimate pitch class. The ordering with the smallest interval is the normal order.
