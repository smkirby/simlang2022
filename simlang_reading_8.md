---
title: Reading 8
description: Innateness and culture in the evolution of language
---


For the last weeks of the course we're going to try and use the modelling tools we have learned so far to answer one of the most fundamental questions in linguistics of the last half century (no pressure, then!). **Is language innate?**

We're going to work towards this question by first understanding exactly what the relationship is between the prior bias of the learner and the distribution of languages that comes out of iterated learning. This is important because one obvious source of the prior (if it isn't learned like you saw last week) is that it reflects whatever innate cognitive biases the learner brings to the task of learning language. A nativist explanation for language states that the distribution of languages we see in the world is a reflection of our innate linguistic knowledge. In other words, we can support a nativist account if there is a straightforward one-to-one relationship between the prior and the distribution of languages that arises from iterated learning (which is sometimes called the *stationary distribution*).

The [Griffiths & Kalish (2007)](https://doi.org/10.1080/15326900701326576) paper sets out to *prove* that this relationship is very straightforward. In fact they show that the stationary distribution is *identical* to the prior. (We've actually seen this already in our first iterated learning lab.) This suggests support for the nativist position (although these authors wouldn't necessarily agree with that view). However, in follow up work, [Kirby, Dowman & Griffiths (2007)](https://doi.org/10.1073/pnas.0608222104) show that this proof only holds for one type of learning strategy, namely one where learners *sample* from the posterior distribution when picking a language. Instead, they show that if learners pick the *MAP* language (the one with the maximum a-posteriori probability) iterated learning can amplify the prior bias.

These papers have some scary looking maths in them, but don't worry too much if you can't follow those bits! They use a fancy technique for working out what the stationary distribution is without having to run really long simulations. This is what allows Griffiths and Kalish (2007) to prove the convergence to the prior result for samplers without having to run an infinite number of simulations! However, in the lab we're going to recreate these results straightforwardly with the simulation models that you're used to using already. So please do concentrate on the ideas in the papers rather than the technical details!

We're left with two important questions, with big concequences for the nativist hypothesis:

1. Are language learners more like samplers or more like MAP learners?
2. Should we expect strong constraints on cross-linguistic variation to be supported by strong prior biases or weak prior biases?

We'll answer these questions next week when we turn to biological (as opposed to cultural) evolution as the source of the prior.


# References

Griffiths, T. L., & Kalish, M. L. (2007). Language evolution by iterated learning with Bayesian agents. *Cognitive science*, 31(3), 441-480.

Kirby, S., Dowman, M., & Griffiths, T. L. (2007). Innateness and culture in the evolution of language. *Proceedings of the National Academy of Sciences*, 104(12), 5241-5245.



# Re-use

This page was written by Simon Kirby. All aspects of this work are licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
