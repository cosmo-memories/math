---
name: Codes & Alphabets
title: "Daguerreo : Codes & Alphabets"
topics: Coding Theory
---
## Alphabets
A ___$$\pmb {q}$$-ary_ alphabet__ is a set of $$\pmb {q}$$ distinct symbols. For example, $$\pmb {\{0, 1\}}$$ is a __$$\pmb {2}$$-ary__ alphabet with two symbols, $$\pmb {0}$$ and $$\pmb {1}$$, and is commonly called __binary__. A ___word___ is a finite sequence of symbols from some alphabet.

<hr id="post-mid">

## Codes

A ___$$\pmb {q}$$-ary code___, usually denoted by $$\pmb {C}$$, is a (non-empty) set of words over a $$\pmb {q}$$-ary alphabet. The words in the set $$\pmb {C}$$ are called ___codewords___. If all codewords in $$\pmb {C}$$ have the same length (number of characters) $$\pmb {n}$$, then $$\pmb {C}$$ is a ___block code___ of ___length $$\pmb {n}$$___.

Two codes $$\pmb{C_1}$$ and $$\pmb{C_2}$$ are ___equivalent___ if one can be transformed into the other using only the following operations:

* [Permuting]({{ site.baseurl }}/concepts/permutation.html) positions of the code.
* Permuting the symbols in a given fixed position.

There exists a [bijection]({{ site.baseurl}}/concepts/bijection.html) $$\pmb {f: C_1 \to C_2}$$ such that, for all $$\pmb {\vec u, \vec v \in C_1}$$, $$\pmb {d(\vec u, \vec v) = d(f(\vec u), f(\vec v))}$$.

### Linear Codes

A ___[linear code]({{ site.baseurl }}/concepts/linearcodes.html) $$\pmb {C}$$___ over $$\pmb {GF(q)}$$ consists of vectors which form a __subspace of [$$\pmb {V(n, q)}$$]({{ site.baseurl }}/concepts/vecspace.html)__.