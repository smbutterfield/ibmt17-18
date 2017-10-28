---
layout: chapter
title: Examples 11a - Voice-leading for Root Position Triads and Seventh Chords
abc: true
---

In your early part writing, you should strive for a simple, clean texture that:
- follows the standard harmonic progressions outlined by circle-of-fifths progressions
    - correctly uses cadences as well as tonic, dominant, and pre-dominant functions
- has the smoothest possible voice-leading for each line
    - the bass can be slightly more disjunct than the upper parts, particularly when using root-position chords
- does not cross voices
- has no spacing or range errors
- avoids incorrect doubling
- resolves tendency tones correctly
- does not create major part-writing errors such as consecutive perfect 5ths/8ves or similar 5ths/8ves

**Circle-of-fifths progressions work because the voice-leading taps into the primary functions of diatonic harmony. If you review Unit 7a, you will remember that we created the harmonic flow chart by simply following good voice-leading between chords that have roots separated by a descending P5/ascending P4. Admittedly, long strings of root-position chords create unmelodic bass lines, but they still represent the strongest voicing for many sonorities. Try harmonizing the following chord progression. Write the soprano line from the given first pitch, and then fill in the inner voices following the guidelines above. (If you are struggling, it is often helpful to establish your ending and then work backward.)**

{% capture ex1 %}X:1
T:Circle-of-fifths triadic progression
M:4/4
L:1
K:C
V:1
c| x| x| x| x|]
V:2 clef=bass
[C,]| [A,,]|[D,]| [G,,]| [C,]|]
w:C:I vi ii V I{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

**Now that you have completed a harmonization, make sure to double-check it for part-writing errors. If you successfully completed it, try changing your melody and trying again.**

## Adding the seventh

**As a theory teacher, I often feel that I spend more time talking about the exceptions to rules than the actual rule itself. Luckily, turning a triad into a seventh chord creates one of the least broken rules. *Typically, the seventh of a chord resolves down by step.* There will be rare instances where this is broken (e.g. pre-determined melody, sequences, etc.), but generally, this rule holds true. Try adding the following two seventh chords to your progression while following this rule.**

{% capture ex2 %}X:2
T:Root-position part-writing with a seventh chord 
T:and root movement by P4/P5
M:4/4
L:1
K:C
V:1
c| x| x| x| x|]
V:2 clef=bass
[C,]| [A,,]|[D,]| [G,,]| [C,]|]
w:C:I vi7 ii V7 I{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

## Exploring options

**Of course, there are multiple chords in our circle of fifths progressions that have root movement by intervals other than 4ths and 5ths. Try harmonizing the following chord progressions while observing our guidelines. Keep track of what types of root movement create the most issues, while coming up with as many possibilities for the following short progressions**

{% capture ex3 %}X:3
T:Short chord progressions
T:Treat each measure as a seperate progression
M:4/4
L:1/4
K:C
V:1
cxxx|| cxxx|| cxxx|| cxxx|]
V:2 clef=bass
[C,] [F,,] [G,,] [C,]|| [C,] [F,,] [G,,] [A,,]|| [C,] [D,] [F,] [G,]|| [C,] [F,,] [G,,] [C,]|]
w:C:I IV V7 I I IV V vi I ii IV V I ii7 V7 I{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

## Function over form (Part 1)

**When you were harmonizing these short chord progressions, which chord progression presented the most issues? For most, it will likely be the deceptive cadence of V resolving to vi. This progression represents a *functional substitutions*. If we consider the voice-leading represented by chords who have roots separated by a descending P5 to be the progenitors of harmonic progression -- iii-vi-ii-V-I -- we must rethink how we approach voice-leading when the progressions do not follow this pattern. (This applies to the IV and vii<sup>o</sup> chords as well, but we need to discuss first-inversion chords in the next topic, 11b, before we are ready for that discussion):**
- When V goes to vi, the vi chord is replacing the tonic function and therefore functions as a I<sup>sub6</sup>

**Therefore, when a V chord precedes a vi chord, the vi chord must follow different *doubling* rules in order to avoid poor voice-leading. With this in mind, harmonize the following progressions; first as the primary functions (i.e. V to I) and then by substituting in the functional substitution (i.e. V to vi.)**

{% capture ex3 %}X:3
T:Using a functional substitution for a deceptive cadence
M:3/4
L:1/4
K:C
V:1
cxx| cxx|]
V:2 clef=bass
[C,] [G,,] [C,]| [C,] [G,,] [A,,]|]
w:C:I V I I V vi{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

**Because the vi chord acts as a replacement for a I chord, we double the scale degree that works best for a I chord, `do`, rather than the standard doubling of the root, `la` or fifth, `mi`. In this progression, it is correct to break standard convention and double the chordal third of the vi chord.**

## Common exceptions

**Chordal third moving to the next chordal third**

{% capture ex3 %}X:3
T:Root-position part-writing with root movement by P4/P5
M:4/4
L:1
K:C
V:1
x| x| x| x| x|]
V:2 clef=bass
[C,]| [A,,]|[D,]| [G,,]| [C,]|]
w:C:I vi ii V I{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

**Frustrated leading tone**


