# How to use abcjs include

In page yml header add `abc: true` to pull in the necessary js files.
For example:

```
---
layout: page
title: ABC include demo
abc: true
---
```

Where you want to add an ABC editor, use the `abc-example.html` include. 
The include must have two variables, `number` and `abc`. 
- `number` must be a unique number on the page, used to make each ABC editor seporate.
- `abc` is the ABC notation. Make sure to give it with no indentation and no extra blank lines. Take care of which quotes you use on the outside, they can not match any quote used inside the notation. i.e. if you use `"` for `clef="alto"` in the notation, you can not use `"` to enclose the variable. Use `'` instead.

For example:

```
{% include abc-example.html number="1" abc="X: 1
M: 4/4
L: 1/8
K: Emin
|:D2|EB{c}BA B2 EB|~B2 AB dBAG|FDAD BDAD|FDAD dAFD|" %}
```

```
{% include abc-example.html number="2" abc='X:1
T: Enharmonic Equivalence
T: Each measure contains two notes that are enharmonically equivalent.
M:2/2
L:1/2
K:C
V:1 name="Treble Clef"
_B ^A |f ^e |^^E ^F |]
V:2 name="Alto Clef" clef="alto"
^G _A |B, _C |^^G, A,|]
V:3 name="Tenor Clef" clef="tenor"
^F, _G, |F, _E, |D, ^^C,|]
V:4 name="Bass Clef" clef="bass"
_D, ^C, |^B,, C, |D, ^^E,|]' %}
```