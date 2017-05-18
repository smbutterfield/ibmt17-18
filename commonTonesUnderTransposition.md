---
layout: post
title: Common Tones under Transposition
---

{{ page.title }}
================

We've already seen that the set class list can tell us some very interesting and important things about the intervallic properties of a set class and its complement.

It can also tell us how many common tones are retained when a set is transposed.  Here's how it works:

Each placeholder in the interval vector tells us how many of a particular interval class are in a given set class. For example, in the (027) set class shown below, all members of that class will have two interval class 5s and one interval class 2. 

*Those numbers also tell us how many common tones are retained when those sets are transposed by a member of that interval class*. That is, because there is a *1* in the second column, a pitch class set belonging to (027) will retain *1* common tone when transposed by either *T2* or *T10*. Because there is a *2* in the fifth column, it will retain *2* common tones when transposed by either *T5* or *T7*.

[![](Graphics/postTonal/commonTonesUnderTransposition.png)](Graphics/postTonal/commonTonesUnderTransposition.png)

You can see this explicitly below. I've taken four arbitrary members of (027)—show on the left—and transposed them in various ways. As indicated above, only *T2*, *T10*, *T5*, or *T7* will keep common tones. Any other transposition will have zero common tones.

[![](Graphics/postTonal/commonTonesUnderTransposition2.png)](Graphics/postTonal/commonTonesUnderTransposition2.png) 

If an interval class vector has a tritone, it will retain twice as many common tones under tritone transposition than is indicated in the vector. For example, the trichord (016) has an interval vector of <100011>. When transposed by *T6*, it will have 2—not 1—common tones.

