---
name: "Syndrome Decoding"
title: "Daguerreo : Syndrome Decoding"
topics: Coding Theory
---

## Syndrome

Let $$\pmb {C}$$ be a __linear code__ with __parity check matrix__ $$\pmb {H}$$.

For any vector $$\pmb {\vec v \in V(n, q)}$$, the ___syndrome of $$\pmb {\vec v}$$___ is $$\pmb {\vec v H^T}$$.

If $$\pmb {\vec v \in C}$$, then $$\pmb {\vec v H^T = \vec 0}$$. Otherwise, $$\pmb {\vec v H^T \neq \vec 0}$$.

For any two vectors $$\pmb {\vec v, \vec u \in V(n, q)}$$, it holds that $$\pmb {\vec v H^T  = \vec u H^T}$$ __if and only if $$\pmb {\vec v}$$ and $$\pmb {\vec u}$$ are in the same coset of $$\pmb {C}$$__. Therefore, the syndrome of a vector is enough to determine which coset it lies in, and vice versa.

## Syndrome Decoding

_[text forthcoming]_