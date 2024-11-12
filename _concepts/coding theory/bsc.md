---
name: Binary Symmetric Channel
title: "Daguerreo : Binary Symmetric Channel"
topics: Coding Theory
---
A ___binary symmetric channel___ is a hypothetical noisy communication channel used to model error probability. We use the __binary alphabet {0, 1}__, and assume that the probability of an error occuring is __independent__ for each bit transmitted.

The probability of error is ___p___, where ___$$0 \leq p \leq 1$$___. In other words, a __0__ is changed to a __1__ with probability ___p___ and vice versa. The probability that an error does _not_ occur is therefore ___p - 1___.

It is expected that ___$$p \lt {1 \over 2}$$___, that is, the probability of error is less than __50%__. (If this was not the case, we could simply assume that all transmissions are incorrect, and thereby construct an equivalent channel with probability of error ___1 - p___.)

For more detail, see [Wikipedia](https://en.wikipedia.org/wiki/Binary_symmetric_channel).