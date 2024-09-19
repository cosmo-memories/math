---
name: Linear Combinations
title: "Daguerreo : Linear Combinations"
topics: [Linear Algebra, Coding Theory]
---
Let $$\pmb {V = \{\vec v_1, . . . , \vec v_n \}}$$ be a set of vectors. A ___linear combination of $$\pmb {V}$$___ is a vector $$\pmb {\vec x}$$ of the form

$$\pmb {\vec x = a_1 \vec v_1 + a_2 \vec v_2 + . . . + a_n \vec v_n}$$

where $$\pmb {a_1, a_2, . . . , a_n}$$ are scalars.

$$\pmb {\langle V \rangle}$$ denotes the ___span of $$\pmb {V}$$___, the set of all vectors which are linear combinations of vectors in $$\pmb {V}$$.

<hr id="post-mid">

## Linear Dependence

If a vector $$\pmb {\vec x}$$ can be written as a linear combination of $$\pmb {V}$$, we say $$\pmb {\vec x}$$ is ___linearly dependent___ on $$\pmb {V}$$.

If a vector $$\pmb {\vec x}$$ __cannot__ be written as a linear combination of $$\pmb {V}$$, we say $$\pmb {\vec x}$$ is ___linearly independent___ of $$\pmb {V}$$.

A set $$\pmb {V = \{\vec v_1, . . . , \vec v_n \}}$$ is linearly independent if the only solution to

$$\pmb {a_1 \vec v_1 + a_2 \vec v_2 + . . . + a_n \vec v_n = \vec 0}$$

is $$\pmb {a_1 = a_2 = . . . = a_n = 0}$$.