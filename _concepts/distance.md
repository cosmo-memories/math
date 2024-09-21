---
name: Distance
title: "Daguerreo : Hamming Distance"
topics: Coding Theory
---
## Hamming Distance
Named after [Richard Hamming](https://en.wikipedia.org/wiki/Richard_Hamming), the ___hamming distance___ (or simply __distance__) between two words (of the __same length _n___, over the same alphabet) is __the number of places in which they differ__. Equivalently, it is the minimum number of positions that need to be modified in order to transform one word into the other.

The hamming distance between two words $$\pmb{\vec u}$$ and $$\pmb{\vec v}$$ is denoted by $$\pmb{d_H(\vec u, \vec v)}$$ or simply $$\pmb{d(\vec u, \vec v)}$$.

<hr id="post-mid">

Given a code $$\pmb{C}$$ containing words of fixed length $$\pmb{n}$$, the following are satisfied for all words $$\pmb{\vec u, \vec v, \vec w \in C}$$:

* Hamming distance is always non-negative:

    $$\pmb{d(\vec u, \vec v) \geq 0}$$.

* The distance is the same regardless of "direction" (ie. which word is being modified into the other):

    $$\pmb{d(\vec u, \vec v) = d(\vec v, \vec u)}$$.

* The distance between any two words is $$\pmb{0}$$ if and only if the words are identical:

    $$\pmb{d(\vec u, \vec v) = 0 \iff \vec u = \vec v}$$.

* Hamming distance satisfies the [triangle inequality](https://en.wikipedia.org/wiki/Triangle_inequality):

    $$\pmb{d(\vec u, \vec v) + d(\vec v, \vec w) \geq d(\vec u, \vec w)}$$.

* The distance between two words is the same as the __weight of their difference__:

    $$\pmb{d(\vec u, \vec v) = w(\vec v - \vec u)}$$.

For two __binary__ codewords $$\pmb{\vec u = (u_1, u_2, . . . , u_n)}$$ and $$\pmb{\vec v = (v_1, v_2, . . . , v_n)}$$:

* The __intersection__ of $$\pmb{\vec u}$$ and $$\pmb{\vec v}$$ is the vector that has __1__ at each position where both vectors also have __1__:

    $$\pmb{\vec u \cap \vec v = (u_1 v_1, u_2 v_2, . . . , u_n v_n)}$$.

<hr id="post-mid">

## Distance of a Code

For a code $$\pmb{C}$$ with size $$\pmb{\geq 2}$$ (ie. containing at least two words), the ___distance of $$\pmb{C}$$___ is the __minimum distance between any two distinct codewords__. The distance of $$\pmb{C}$$ is denoted by $$\pmb{d(C)}$$.

If $$\pmb {C}$$ is a __linear code__, then $$\pmb {d(C)}$$ is equal to the __minimum weight of all non-zero codewords__.