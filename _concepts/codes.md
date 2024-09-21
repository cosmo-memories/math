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

### Linear Codes

A ___linear code $$\pmb {C}$$___ over $$\pmb {GF(q)}$$ consists of vectors which form a __subspace of [$$\pmb {V(n, q)}$$]({{ site.baseurl }}/concepts/vecspace.html)__.

Linear codes are commonly discussed in terms of their paramaters:

* $$\pmb {n}$$: the __length__ of $$\pmb {C}$$, that is, the number of symbols in a codeword.

* $$\pmb {k}$$: the __dimension__ of $$\pmb {C}$$; see [vector spaces]({{ site.baseurl }}/concepts/vecspace.html).

* $$\pmb {d}$$: the __distance__ of $$\pmb {C}$$, which for linear codes is equal to the minimum weight of all non-zero codewords.

A linear code with the above parameters is called an ___$$\pmb {[n, k, d]}$$-code___ or ___$$\pmb {[n, k, d]_q}$$-code___.

The ___size___ of $$\pmb {C}$$ refers to the number of codewords, and is equal to $$\pmb {q^k}$$.

It is common to represent a linear code in the form of a ___generator matrix___ _[link forthcoming]_.