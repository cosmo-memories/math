---
name: "Standard Arrays & Cosets"
title: "Daguerreo : Standard Arrays & Cosets"
topics: Coding Theory
---

## Cosets

Let $$\pmb {V}$$ be a vector space and $$\pmb {W}$$ be a subspace of $$\pmb {V}$$. For all $$\pmb {\vec a \in V}$$, the set $$\pmb {\vec a + W}$$ is defined as:

$$\pmb {\vec a + W = \{ \vec a + \vec b \space \vert \space \vec b \in W \}}$$

In other words, the set contains all posible combinations of $$\pmb {\vec a}$$ with vectors in the subspace $$\pmb {W}$$. This set is called a ___coset___ of $$\pmb {W}$$, and $$\pmb {\vec a}$$ is the ___coset leader___.

For a code $$\pmb {C}$$ which is a $$\pmb {k}$$-dimensional subspace of $$\pmb {V(n, q)}$$:

* There are __$$\pmb {q^k}$$ vectors in every coset__.

* There are __$$\pmb {q^{n - k}}$$ cosets in total__.

The cosets of $$\pmb {W}$$ form a partition of $$\pmb {V}$$; that is, every vector in $$\pmb {V}$$ is in __exactly one__ coset of $$\pmb {W}$$. If $$\pmb {\vec a + W}$$ is a coset and $$\pmb {\vec b \in \vec a + W}$$, then $$\pmb {\vec a + W = \vec b + W}$$. In other words, a coset can be assigned a different leader and still produce the same set.

<hr id="post-mid">

## Slepian Standard Array

The ___standard array___ of a code $$\pmb {C}$$ in a structure that displays the cosets of $$\pmb {C}$$.

Cosets are listed one per row; the first row is $$\pmb {\vec 0 + C}$$, which is simply __the set of all codewords__.

For the following row, choose any __minimum weight vector__ $$\pmb {\vec v_1 \in V(n,q)}$$ and list $$\pmb {\vec v_1 + C}$$. Repeat until all vectors in $$\pmb {V}$$ are listed.