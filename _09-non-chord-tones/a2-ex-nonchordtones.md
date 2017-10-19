---
layout: chapter
title: 9a Examples - Non-chord Tones
abc: true
---

**We will the following simple progression as a template for writing non-chord tones. Start by providing Roman numerals and leadsheet symbols.**

{% capture ex1 %}X:1
T:A simple phrase
M:4/4
L:1/2
Q:1/4=100
K:F
V:1
[FA]| [DG] [EB]| [FA] [FD]| [DD] [CE]| H[C2F2]|]
V:2 clef=bass
[F,C]| [B,,D] [CC,]| [CF,] [D,B,]| [B,,G,] [G,C,]| H[A,2F,,2]|]{% endcapture %}
{% include abc-example.html number="1" abc=ex1 %}

**Using this framework we can add some of the NCTs that we have already studied. The following example incorporate multiple examples of each of these to create an (overly) florid example. Identify each of the non-chord tones.**

{% capture ex2 %}X:2
T:With added suspensions, passing tones, and neighbor tones
M:4/4
L:1/2
Q:1/4=80
K:F
V:1
[FA]| [D/2G/2][D/2A/2] [EB]| [F/2A/2][F/2G/2] [F/2D/2][E/2D/2]| [DD] [CE]| H[C2F2]|]
V:2 clef=bass
[F,C]| [B,,D] [D/2C,/2][C/2C,/2]| [CF,] [D,B,]| [B,,/2G,/2][B,,/2A,/2] [G,C,]| H[A,2F,,2]|]
w:F:I ii6 V7 _ I IV6 ii6 _ V I{% endcapture %}
{% include abc-example.html number="2" abc=ex2 %}

**There are many other types of NCTs, so we will now use our simple progression to demonstrate examples of each of them. Compare the examples below to the original progression to determine what has changed; this change is the NCT. As you do this, use the the three characteristics discussed in the overview -- preparation, NCT, and resolution -- to create a definition for each NCT. Once you have a working definition, see if the other other descriptors (such as upper/lower, ascending/descending, chromatic/diatonic, or accented/non-accented) can be applied to each NCT.**

## Retardations (RET)

**Which other NCT does a retardation resemble?**

{% capture ex3 %}X:3
T:With added retardations
M:4/4
L:1/2
Q:1/4=100
K:F
V:1
[FA]| [DG] [EB]| [E/2A/2][F/2A/2] [FD]| [DD] [CE]| [C/2E/2]H[C/2F/2]|]
V:2 clef=bass
[F,C]| [B,,D] [CC,]| [CF,] [D,B,]| [B,,G,] [G,C,]| H[A,F,,]|]
w:F:I ii6 V7 I IV6 ii6 V I{% endcapture %}
{% include abc-example.html number="3" abc=ex3 %}

## Neighbor groups (NG) - also called "double neighbor tones"

**How does the neighbor group relate to a neighbor tone?**

{% capture ex4 %}X:4
T:With added neighbor groups
M:4/4
L:1/2
Q:1/4=100
K:F
V:1
[FA]| [DG] [EB]| [FA] [FD]| [DD] [CE]| H[C2F2]|]
V:2 clef=bass
[F,C]| [B,,D] [C/4C,/4][D/4C,/4][C/4C,/4][B,/4C,/4]| [CF,] [D,B,]| [B,,/4G,/4][B,,/4F,/4][B,,/4G,/4][B,,/4A,/4] [G,C,]| H[A,2F,,2]|]
w:F:I ii6 V7 _ _ _ I IV6 ii6 _ _ _ V I{% endcapture %}
{% include abc-example.html number="4" abc=ex4 %}

## Appogiaturas

**The following example includes NCT appogiaturas as well as appogiaturas figures. What is the difference? What do they have in common?**

{% capture ex5 %}X:5
T:With added appogiaturas
M:4/4
L:1/2
Q:1/4=100
K:F
V:1
[FA]| [DG] [EB]| [FA] [FD]| [DD] [CE]| H[C2F2]|]
V:2 clef=bass
[F,C]| [B,,D] [CC,]| [CF,] [D,B,]| [B,,G,] [G,C,]| H[A,2F,,2]|]
w:I ii6 V7 I IV6 ii6 V I{% endcapture %}
{% include abc-example.html number="5" abc=ex5 %}

## Escape tones

{% capture ex6 %}X:6
T:With added escape tones
M:4/4
L:1/2
Q:1/4=100
K:F
V:1
[FA]| [DG] [EB]| [FA] [FD]| [DD] [CE]| H[C2F2]|]
V:2 clef=bass
[F,C]| [B,,D] [CC,]| [CF,] [D,B,]| [B,,G,] [G,C,]| H[A,2F,,2]|]
w:I ii6 V7 I IV6 ii6 V I{% endcapture %}
{% include abc-example.html number="6" abc=ex6 %}

## Incomplete neighbor tones

{% capture ex7 %}X:7
T:With added incomplete neighbor tones
M:4/4
L:1/2
Q:1/4=100
K:F
V:1
[FA]| [DG] [EB]| [FA] [FD]| [DD] [CE]| H[C2F2]|]
V:2 clef=bass
[F,C]| [B,,D] [CC,]| [CF,] [D,B,]| [B,,G,] [G,C,]| H[A,2F,,2]|]
w:I ii6 V7 I IV6 ii6 V I{% endcapture %}
{% include abc-example.html number="7" abc=ex7 %}

## Pedals

{% capture ex8 %}X:8
T:With added an added pedal point
M:4/4
L:1/2
Q:1/4=100
K:F
V:1
[FA]| [DG] [EB]| [FA] [FD]| [DD] [CE]| H[C2F2]|]
V:2 clef=bass
[F,C]| [F,B,] [F,C]| [CF,] [D,B,]| [B,,G,] [G,C,]| H[A,2F,,2]|]
w:I ii6 V7 I IV6 ii6 V I{% endcapture %}
{% include abc-example.html number="8" abc=ex8 %}