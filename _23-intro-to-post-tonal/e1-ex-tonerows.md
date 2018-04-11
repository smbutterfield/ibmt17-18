---
layout: chapter
title: 23e Examples - Serialism and Tone Rows
abc: true
---

For many people, the terms *tone row* and *matrix* are synonymous with post-tonal theory, but to this point, we haven't even mentioned them. (If you have never heard of either of these terms, don't worry. We'll get there.)

We haven't discussed them yet, because if you understand set theory, you will have no problem understanding what a tone row is and how we use them in analysis.

## Starting small

First, we need to reaffirm your understanding of set classes. To do this, let's start by writing out each unique, normal-form pc set represented in the set class of (013). What factors increase the number of unique pc sets? What limits the number of pc sets?

Before you began, you probably realized that there would be twenty-four possibilities. Because each of the pc sets will be in normal form, we know that there is only *one* pc set for each possible starting pitch. We can represent these using transposition notation.
- T<sub>0</sub>[0,1,3] = [0,1,3]
- T<sub>1</sub>[0,1,3] = [1,2,4]
- T<sub>2</sub>[0,1,3] = [2,3,5]
- T<sub>3</sub>[0,1,3] = [3,4,6]
- T<sub>4</sub>[0,1,3] = [4,5,7]
- T<sub>5</sub>[0,1,3] = [5,6,8]
- T<sub>6</sub>[0,1,3] = [6,7,9]
- T<sub>7</sub>[0,1,3] = [7,8,t]
- T<sub>8</sub>[0,1,3] = [8,9,e]
- T<sub>9</sub>[0,1,3] = [9,t,0]
- T<sub>t</sub>[0,1,3] = [t,e,1]
- T<sub>e</sub>[0,1,3] = [e,0,2]

There are a further twelve unique pc sets that result from inverting our prime form pc set. Of course, for each of these, you should normalize the pc set after inversion.
- T<sub>0</sub>I[0,1,3] = [9,e,0]
- T<sub>1</sub>I[0,1,3] = [t,0,1]
- T<sub>2</sub>I[0,1,3] = [e,1,2]
- T<sub>3</sub>I[0,1,3] = [0,2,3]
- T<sub>4</sub>I[0,1,3] = [1,3,4]
- T<sub>5</sub>I[0,1,3] = [2,4,5]
- T<sub>6</sub>I[0,1,3] = [3,5,6]
- T<sub>7</sub>I[0,1,3] = [4,6,7]
- T<sub>8</sub>I[0,1,3] = [5,7,8]
- T<sub>9</sub>I[0,1,3] = [6,8,9]
- T<sub>t</sub>I[0,1,3] = [7,9,t]
- T<sub>e</sub>I[0,1,3] = [8,t,e]

Each one of these twenty-four pc sets contains a unique collection of pitch classes. Without using the word "inversion", how would you describe the relationship between T<sub>0</sub> and T<sub>0</sub>I? 

## Visually representing a set class

In the above example, you could describe T<sub>0</sub> and T<sub>0</sub>I as the reverse order of the same *intervals*, but the only obvious correlation between the actual *pitch classes* is that both of the pc sets contain 0 -- which happens to be the interval of transposition for those two sets. (The interval of transposition is the "0" in T<sub>0</sub>.) If you look at each pair of transposed and inverted pc sets, you will notice the same thing; they always share the interval of transposition. If you wanted to represent this visually, you could plot each transposition and inversion on a chart in which this pivot pitch for each transposition became a center pitch and had the inversion and transposition branching out. Look at our trichord charted this way below.

Inv pc set | inv pc 1 | inv pc 2 | **common pc** | tran pc 2 | tran pc 3 | Tran pc set
--- | --- | --- | --- | --- | --- | ---
T<sub>0</sub>I | 9 | e | 0 | 1 | 3 | T<sub>0</sub>
T<sub>1</sub>I | t | 0 | 1 | 2 | 4 | T<sub>1</sub>
T<sub>2</sub>I | e | 1 | 2 | 3 | 5 | T<sub>2</sub>
T<sub>3</sub>I | 0 | 2 | 3 | 4 | 6 | T<sub>3</sub>
T<sub>4</sub>I | 1 | 3 | 4 | 5 | 7 | T<sub>4</sub>
T<sub>1</sub>I | 2 | 4 | 5 | 6 | 8 | T<sub>5</sub>
T<sub>6</sub>I | 3 | 5 | 6 | 7 | 9 | T<sub>6</sub>
T<sub>7</sub>I | 4 | 6 | 7 | 8 | t | T<sub>7</sub>
T<sub>8</sub>I | 5 | 7 | 8 | 9 | e | T<sub>8</sub>
T<sub>9</sub>I | 6 | 8 | 9 | t | 0 | T<sub>9</sub>
T<sub>t</sub>I | 7 | 9 | t | e | 1 | T<sub>t</sub>
T<sub>e</sub>I | 8 | t | e | 0 | 2 | T<sub>e</sub>

Here, the "common pc" column shows the pitch class that is common to both the inversion and the transposition pc sets. (Note that to create this chart, the inverted form of the pc set is written in descending form rather than ascending form, so you must read it backwards to find its normal form.) You can make a chart like this for any pc set, and you can see how helpful this would be if you were analyzing a piece of music that had this trichord present. Rather than only looking for intervallic patterns, you could quickly refer to your chart to identify whether a specific trichord belongs to this set class.

## Expanding the set

What if we were to expand this technique? What would the above chart look like for a pc set with all twelve pitch classes? Before we explore that, let's set some ground rules. If you were to use normal form, there is technically only one prime form for an aggregate pitch set: (0123456789te). However, if we treat the intervallic pattern as a fixed part of the pc set -- meaning we do *not* put the pc set into normal form -- then we can create nearly a million different distinct combinations of all twelve pitch classes.

With this in mind, try creating the first two lines of the above graph (that would be T<sub>0</sub>/T<sub>0</sub>I and T<sub>1</sub>/T<sub>1</sub>I) for the following pc set:
T<sub>0</sub> = (0,2,4,6,8,t,1,3,5,7,9,e)

What do you notice as you work through this? Can you think of different methods for creating T<sub>1</sub>I rather than just mirroring T<sub>1</sub>? While the chart above was not too unwiedly for addressing all possible variations on a trichord, can you think of a way to create a chart that shows every combination (transposed and inverted) of an aggregate pc set that would take less space than the clunky chart above?

## The tone row matrix

The answer to the pc set would take up too much screen for me to succinctly write in a table here, but in plain text the order would be:
- T<sub>0</sub>I 1 3 5 7 9 e 2 4 6 8 t **0** 2 4 6 8 t 1 3 5 7 9 e T<sub>0</sub>
- T<sub>1</sub>I 2 4 6 8 t 0 3 5 7 9 e **1** 3 5 7 9 e 2 4 6 8 t 0 T<sub>1</sub>

What if rather than writing T<sub>0</sub> and T<sub>0</sub>I in a straight line, we rotated the inversion pc set, T<sub>0</sub>I, downward at 90 degree angle to create a verical column? This would create the outline for a 12 by 12 grid with T<sub>0</sub> as the top row and T<sub>0</sub>I as the first column.

-- | T<sub>0</sub>I |  |  |  |  |  |  |  |  |  |  
--- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | ---
T<sub>0</sub> | 0 | 2 | 4 | 6 | 8 | t | 1 | 3 | 5 | 7 | 9 | e
-- | t |  |  |  |  |  |  |  |  |  |  |  
-- | 8 |  |  |  |  |  |  |  |  |  |  |  
-- | 6 |  |  |  |  |  |  |  |  |  |  |  
-- | 4 |  |  |  |  |  |  |  |  |  |  |  
-- | 2 |  |  |  |  |  |  |  |  |  |  |  
-- | e |  |  |  |  |  |  |  |  |  |  |  
-- | 9 |  |  |  |  |  |  |  |  |  |  |  
-- | 7 |  |  |  |  |  |  |  |  |  |  |  
-- | 5 |  |  |  |  |  |  |  |  |  |  |  
-- | 3 |  |  |  |  |  |  |  |  |  |  |  
-- | 1 |  |  |  |  |  |  |  |  |  |  |  


## Serialism and 12-tone music

Before we go further, we should briefly define the genre of music most associated with set theory. (Although set theory can be used to study *any* type of music as long as it divides the octave into twelve pitches.) *Serialism* is any music in which some aspect of the composition is based on a pre-defined repeatable pattern; this can be the melodic intervals, harmonic intervals, harmonies, rhythm, or any other aspect of music that could be described in a series.

*12-tone music* is a sub-genre within serialism in which a fixed series of all twelve pitches is used to generate both the melodic and harmonic content of the piece. There are a variety of ways in which composers have employed this, but generally, all twelve pitches must be used before a pitch can be repeated. The series that determines the order of all twelve pitch classes is called a *tone row*. To provide compositional variety, the tone row may be altered to any of its transpositions or inversions, and any of row may also be played in *retrograde* -- all pitches in reverse order. So from this, there are four forms of a tone row.
- Prime (P) - a tone row or any of its transpositions
- Retrograde (R) - any prime row played in reverse order
- Inversion (I) - the inversion of the tone row and all its transpositions
- Retrograde inversion (RI) - any inverted row played in reverse order

Because any of these tone row orders can start on all twelve pitches, there are forty-eight possible arrangements of any tone row. We label these using the abbreviations above (P, R, I, and RI) followed by a subscript number to represent the transposition. (e.g. P<sub>5</sub> or RI<sub>6</sub>).

## Tone row matrix

Given the sheer amount of variation, it makes starting an analysis of a 12-tone piece difficult, so we have a developed a visual representation of the row similar to the exercise that we created using our (013) trichord above.

Think about an aggregate in same way wand have class find its inversion
    First by interval for a row that doesn't start on zero
    Then by zeroing the row first

Matrix
    Fixed-zero vs movable zero
    Fixed-zero format
        Standard fixed zero vs prime fixed zero
        Changes how it looks, but doesn't affect naming which is why we use fixed zero instead of movable
        Greatly speeds up the matrix creation process
    Naming of retrograde and retrograde inversion rows is based on corresponding prime and inverted rows, NOT the starting pitch of the retro row

