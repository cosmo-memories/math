---
name: Vector Spaces
title: "Cosmo's Math : Vector Spaces"
topics: [Group Theory, Coding Theory, Linear Algebra]
---

Let $$\pmb {\mathbb F}$$ be a field whose elements are called ___scalars___.

Let $$\pmb {V}$$ be a __non-empty set__ whose elements are called __vectors__.

A ___vector space over a field $$\pmb {\mathbb F}$$___ consists of a non-empty set of vectors $$\pmb {V}$$ together with a __binary operation $$\pmb {+}$$__ (___vector addition___) and a __binary function__ (___scalar multiplication___). The following properties must be satisfied for all $$\pmb {\vec u, \vec v, \vec w \in V}$$ and all $$\pmb {a, b \in \mathbb F}$$:

* Vector addition ($$\pmb {+}$$) is __associative__ and __commutative__:

    $$\pmb {\vec u + (\vec v + \vec w) = (\vec u + \vec v) + \vec w}$$.

    $$\pmb {\vec u + \vec v = \vec v + \vec u}$$.

* Vector addition has an __identity element__:

    There exists an element $$\pmb {\vec 0 \in V}$$, the ___zero vector___, such that $$\pmb {\vec v + \vec 0 = \vec v}$$ for all $$\pmb {\vec v \in V}$$.

* Vector addition has __inverse elements__:

    For each $$\pmb {\vec v \in V}$$, there exists an element $$\pmb {\vec {-v} \in V}$$ such that $$\pmb {\vec v + (\vec {-v}) = \vec 0}$$.

* $$\pmb {V}$$ is __closed__ under scalar multiplication:

    $$\pmb {a \vec v \in V}$$.

* Scalar multiplication is __distributive__:

    $$\pmb {a ( \vec u + \vec v) = a \vec u + a \vec v}$$.

    $$\pmb {(a + b) \vec v = a \vec v + b \vec v}$$.

* Scalar multiplication has an __identity element__:

    $$\pmb {1 \vec v = \vec v}$$, where $$\pmb {1}$$ is the multiplicative identity of $$\pmb {\mathbb F}$$.

* Scalar multiplication is compatible with field multiplication:

    $$\pmb {a(b\vec v) = (ab) \vec v}$$.

The (unique) ___n-dimensional vector space over [$$\pmb {GF(q)}$$]({{ site.baseurl }}/concepts/fields.html)___ is denoted by $$\pmb {V = V(n, q)}$$.