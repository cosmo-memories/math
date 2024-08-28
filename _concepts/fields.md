---
name: Groups & Fields
title: "Cosmo's Math : Groups & Fields"
topics: Group Theory
---
## Groups

A ___group___ is an ordered pair $$\pmb {(G, \cdot)}$$, where $$\pmb {G}$$ is a __non-empty set of elements__, and $$\pmb {\cdot}$$ is an associated __binary operation__. This operation associates each pair of elements in the set with another element in the set. This operation must satisfy the following three ___group axioms___:

* __Associativity__:

    For all $$\pmb {a, b, c \in G}$$, it holds that $$\pmb {(a \cdot b) \cdot c = a \cdot (b \cdot c)}$$.

* __Identity element__:

    There is a unique element $$\pmb {e \in G}$$ such that, for all $$\pmb {a \in G}$$, it holds that $$\pmb {e \cdot a = a \cdot e = a}$$.

* __Inverse elements__:

    For each element $$\pmb {a \in G}$$, there exists a unique element $$\pmb {a^{-1} \in G}$$ such that $$\pmb {a \cdot a^{-1} = a^{-1} \cdot a = e}$$.

Additionally, a group is ___abelian___ if the following also holds:

* __Commutativity__:

    For all $$\pmb {a, b \in G}$$, it holds that $$\pmb {a \cdot b = b \cdot a}$$.

<hr id="post-mid">

## Fields

A ___field___ is a set of elements ($${\pmb {\mathbb F}}$$) together with __two binary operations__ ($$\pmb {+}$$ and $$\pmb {\cdot}$$) defined on the set. As with groups, each binary operation takes a pair of elements from the set and associates them with another element of the set. The following properties must be satisfied:

* __Closure__:

    $${\pmb {\mathbb F}}$$ is closed under $$\pmb {+}$$ and $$\pmb {\cdot}$$. For all $$\pmb {a, b \in \mathbb F}$$, it holds that $$\pmb {a + b \in \mathbb F}$$ and $$\pmb {a \cdot b \in \mathbb F}$$.

* __Associativity__:

    For all $$\pmb {a, b, c \in \mathbb F}$$, it holds that $$\pmb {(a + b) + c = a + (b + c)}$$ and $$\pmb {(a \cdot b) \cdot c = a \cdot (b \cdot c)}$$.

* __Commutativity__:

    For all $$\pmb {a, b \in \mathbb F}$$, it holds that $$\pmb {a + b = b + a}$$ and $$\pmb {a \cdot b = b \cdot a}$$.

* __Distributivity__:

    For all $$\pmb {a, b, c \in \mathbb F}$$, it holds that $$\pmb {a \cdot (b + c) = a \cdot b + a \cdot c}$$.

* __Additive identity__:

    There is a unique element $$\pmb {0 \in \mathbb F}$$ such that, for all $$\pmb {a \in \mathbb F}$$, it holds that $$\pmb {a + 0 = a}$$.

* __Multiplicative identity__:

    There is a unique element $$\pmb {1 \in \mathbb F}$$, $$\pmb {1 \neq 0}$$ such that, for all $$\pmb {a \in \mathbb F}$$, it holds that $$\pmb {a \cdot 1 = a}$$.

* __Additive inverses__:

    For each element $$\pmb {a \in \mathbb F}$$, there exists a unique element $$\pmb {-a \in \mathbb F}$$ such that $$\pmb {a + (-a) = 0}$$.

* __Multiplicate inverses__:

    For each element $$\pmb {a \in \mathbb F}$$, $$\pmb {a \neq 0}$$, there exists a unique element $$\pmb {a^{-1} \in \mathbb F}$$ such that $$\pmb {a \cdot a^{-1} = 1}$$.

Note that $$\pmb {(\mathbb F, +)}$$ and $$\pmb {(\mathbb F \setminus \{ 0 \}, \cdot)}$$ are both abelian groups, and a field may thus be viewed as a "marriage" of two abelian groups via distributivity.

$$\pmb {\mathbb Z _m = \{ 0, 1, . . ., m - 1\}}$$ is a field if and only if __$$\pmb {m}$$ is a prime number__.

In general, for $$\pmb {m \in \mathbb Z^+}$$, there exists a (finite) field with $$\pmb {m}$$ elements if and only if __$$\pmb {m}$$ is a prime power__; in other words, $$\pmb {m = p^n}$$ for some prime $$\pmb {p}$$. Aditionally, if $$\pmb {m}$$ is a prime power, then the field with $$\pmb {m}$$ elements is __unique__; such a field is known as a ___Galois field___ (or ___[finite field](https://en.wikipedia.org/wiki/Finite_field)___) and is denoted by $$\pmb {GF(m)}$$.

If $$\pmb {m}$$ is prime, then $$\pmb {GF(m) = \mathbb Z _m}$$.