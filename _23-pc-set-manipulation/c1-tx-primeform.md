---
layout: chapter
title: 23c Examples - PC Set Prime Form
abc: true
---

Pitch-class integer notation and the two primary forms of manipulation -- transposition and inversion -- allow for a tremendous amount of flexibility in analysis. This flexibility comes with the drawback of making comparison difficult, because there is no guarantee that a pc set is in the same order. For this reason, we use normal form to ensure that our comparisons between pc sets are built in a consistent manner. This is also why you should always normalize a pc set after inverting it.

Theoretically, we can determine whether any two pc sets are related by transposition, inversion, or both. To try this, study the following four trichords. How are they related? What method(s) did you use to find the relationships? As you work through this, keep track of the manipulations you make to find compare them. Hint: It will be helpful to make sure that you are always working with the normal form.
- (2,9,6)
- (8,4,1)
- (e,2,7)
- (6,2,8)

## Set class

For fairly simple trichords such as these, there are a variety of methods you could use to compare them. Some people will write them using traditional notation on a staff, yet others will attempt to visualize them on clock or number line. These visual methods may work to a degree for a simple trichord but fail on two accounts
- It is difficult to scale to larger, denser pc sets.
- It is difficult to see the relationship for anything other than transposition.

For these reasons, set theory has a system to reduce and compare any pc set into a group of all related pc sets. Any two pc sets that are related by transposition and/or inversion are considered to be part of the same *set class*. All of the trichords listed above belong to the same set class, and we can show this using simple manipulations.

If we put each of them into normal form, we get:
- [2,6,9]
- [1,4,8]
- [7,e,2]
- [2,6,8]

Just by doing this, it easy to use addition and subtraction to show that the first and third trichords are directly related by transposition:
- T<sub>5</sub>[2,6,9] = [7,e,2])

And the second and fourth are related in the same manner 
- T<sub>1</sub>[1,4,8] = [2,6,8]

Because an inverted pc set often has no common tones with its original pc set, it is more difficult to see inverted relationships. For this, it would be easier to a "standard" normal form to which we could compare the other. For this, let's try reducing both sets above to begin with 0. If we do this the first pair of pc sets becomes [0,4,7] and the second pair becomes [0,3,7]. You can see that they are similar in that they both use pitch classes 0 and 7, but are they related by inversion? Let's try inverting one of them, normalizing it, and then reducing it to a normal form that begins on 0.

- [2,6,9] reduces to [0,4,7] (by transposing by -2)
- [0,4,7] inverts to [0,8,5]
- [0,8,5] normalizes to [5,8,0]
- [5,8,0] reduces to [0,3,7] (by transposing by -5)

Therefore, we can see that all four of our original trichords are related by transposition and inversion. Or we could also say that *they all belong to the same **set class**.*

## Prime form

The process that we just demonstrated is the actual method for finding a pc set's *prime form*. Prime form is the "most reduced" version of any pc set. It will always start with 0, and it is used to denote an entire *set class* -- all possible transpositions and inversions of a given pc set.

In the above trichords, we had two possible prime forms [0,3,7] and [0,4,7]. These two trichords represent the reduced trichord of both inversions of this pc set. To determine which is prime form, we apply the same tie-breakers that we used when determining normal form: start by comparing the outermost intervals and then work your way inward. Both of these trichords have an outer interval of 7, but [0,3,7] has a smaller second interval (i.e. 0 to 3 is smaller than 0 to 4). Therefore, the prime form of **all** of the above trichords is:

(037)

Notice the notation of prime form. For this we use parentheses only with no commas. (All of the notation that we use for pc sets -- unordered, normal, and prime forms -- was standardized by Joseph Straus in his *Introduction to Post-tonal Theory*.)

