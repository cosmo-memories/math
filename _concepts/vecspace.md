---
name: Vector Spaces
title: "Daguerreo : Vector Spaces"
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

The (unique) ___n-dimensional vector space over [$$\pmb {GF(q)}$$]({{ site.baseurl }}/concepts/fields.html)___ is denoted by $$\pmb {V = V(n, q)}$$. This space contains $$\pmb {q^n}$$ unique vectors.

<hr id="post-mid">

## In Coding Theory

If __$$\pmb {q}$$ is prime__, then the vector space $$\pmb {V(n, q)}$$ consists of all words of length $$\pmb {n}$$ over the alphabet $$\pmb {\{ 0, 1, . . . , p-1 \}}$$. As such, any code of length $$\pmb {n}$$ over this alphabet is a __subset of $$\pmb {V(n,q)}$$__.

If this subset is also a __subspace__ (see below), then the code is __[linear]({{ site.baseurl }}/concepts/codes.html)__.

<hr id="post-mid">

## Subspaces

A ___subspace___ of $$\pmb {V}$$ is a subset of $$\pmb {V}$$ that still fulfils the above conditions and thus is also a vector space.

Note that $$\pmb {V}$$ is also a subspace of itself, and that $$\pmb {\{ \vec 0 \}}$$ is a subspace of every vector space.

To show that a non-empty subset $$\pmb {X \subseteq V}$$ over a field $$\pmb {\mathbb F}$$ is a subspace, show that $$\pmb {X}$$ is

* Closed under vector addition:

    If $$\pmb {\vec u, \vec v \in X}$$, then $$\pmb {\vec u + \vec v \in X}$$.

* Closed under scalar multiplication:

    If $$\pmb {a \in \mathbb F}$$, then $$\pmb {a \vec v \in X}$$.

### Orthogonal Subspace

If $$\pmb {W}$$ is a subspace of $$\pmb {V}$$, then the following set is also a subspace of $$\pmb {V}$$:

$$\pmb {W^\perp = \{ \vec v \in V \vert \vec v \cdot \vec w = 0 \text{ for all } \vec w \in W \}}$$

This subspace, $$\pmb {W^\perp}$$ (pronounced "W perp"), is called the ___orthogonal subspace of $$\pmb {W}$$___, and contains __every vector in $$\pmb {V}$$ that is orthogonal to every vector in $$\pmb {W}$$__. Note that $$\pmb {(W^\perp)^\perp = W}$$. Also note that, per the __Rank-Nullity theorem__ _[link forthcoming]_:

$$\pmb {\dim (W) + \dim (W^\perp) = \dim (V)}$$

In coding theory, if $$\pmb {C}$$ is a subspace of $$\pmb {V(n, q)}$$ (and therefore is a linear code), then $$\pmb {C^\perp}$$ is the ___dual code___ of $$\pmb {C}$$.