---
name: Decoding
title: "Daguerreo : Decoding"
topics: Coding Theory
---

## Detection

If $$\pmb {d_H(C) \geq k + 1}$$, $$\pmb {C}$$ is a ___k error detecting___ code, and can ___detect_ up to _k_ errors__ in a received codeword.

## Correction

If $$\pmb {d_H(C) \geq 2k + 1}$$, $$\pmb {C}$$ is a ___k error correcting___ code, and can ___correct_ up to _k_ errors__ in a received codeword.

<hr id="post-mid">

## Minimum Distance Decoding

Also known as __nearest neighbour decoding__, this method decodes a received word $$\pmb {\vec v}$$ to the codeword with the smallest Hamming distance from $$\pmb {\vec v}$$. In other words, $$\pmb {\vec v}$$ is decoded to a codeword $$\pmb {\vec u \in C}$$ such that:

$$\pmb {d_H(\vec v, \vec u) = \text{min} \{ \ d(\vec v, \vec c) \ \vert \ \vec c \in C \ \}}$$

When transmission occurs over a __binary symmetric channel__ with probability of error $$\pmb {0 \leq p \lt {1 \over 2} }$$, minimum distance decoding is equivalent to __maximum likelihood decoding__; $$\pmb {P(\vec u \ \text{sent} \ \vert \ \vec v \ \text{received})}$$ is maximal when $$\pmb {d(\vec v, \vec u)}$$ is minimal.

<hr id="post-mid">

## Maximum Likelihood Decoding

__Maximum likelihood decoding__ decodes the received word $$\pmb {\vec v}$$ to a codeword $$\pmb {\vec u \in C}$$ that maximizes $$\pmb {P(\vec u \ \text{sent} \ \vert \ \vec v \ \text{received})}$$, the probability that codeword $$\pmb {\vec u}$$ was sent given that $$\pmb {\vec v}$$ was received; see [Bayes' theorem]({{ site.baseurl }}/concepts/bayes.html).