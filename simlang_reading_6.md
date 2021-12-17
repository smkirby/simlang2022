---
title: Reading 6
description: The Evolution of Compositionality
---


This week we will be pulling together the three tools we have introduced in the course so far – models of learning, transmission, and communication to build a more complete model of language transmission. Languages are transmitted from person to person via a cycle of learning and use, where people apply the grammar they have learned to use language to communicate, and the language they produce in communication forms the basis for learning in other individuals. If we want to model language transmission in the wild in a satisfying way, we therefore need to include (at least!) these three components in our models.

In order to explore how learning and communication interact to shape language systems, we’ll look at some of our recent work on the evolution of compositional structure. I’d like you to read [Kirby et al. (2015)](https://doi.org/10.1016/j.cognition.2015.03.016). That paper lays out both a computational model (featuring Bayesian learning, iterated learning, and a simple form of RSA model) plus an experiment with human participants testing some of the predictions of the model. The model works in the same way as the models you have seen so far – there’s a hypothesis space, a prior, and a likelihood function (which includes some RSA-inspired features). It’s got some extra bells and whistles (individuals can learn a distribution over grammars rather than a single grammar), but those extra bits of the model actually don’t add too much extra, so don’t stress if you don’t follow those details. We’ll be working with a simpler version of this same model in Lab 6, which produces basically the same behaviours.

If you want some more historical background, you can look at our first iterated learning experiment [(Kirby et al., 2008)](https://www.pnas.org/content/pnas/105/31/10681.full.pdf) and a paper that summarises some of the very early work building simulations of the emergence of compositionality [(Kirby and Hurford, 2002)](https://link.springer.com/chapter/10.1007/978-1-4471-0663-0_6).

# References

Kirby, S., Cornish, H., & Smith, K. (2008). Cumulative cultural evolution in the laboratory: An experimental approach to the origins of structure in human language. *Proceedings of the National Academy of Sciences*, 105(31), 10681-10686.

Kirby S., Hurford J.R. (2002) The Emergence of Linguistic Structure: An Overview of the Iterated Learning Model. In: Cangelosi A., Parisi D. (eds) *Simulating the Evolution of Language*. Springer, London.

Kirby, S., Tamariz, M., Cornish, H., & Smith, K. (2015). Compression and Communication in the Cultural Evolution of Linguistic Structure. *Cognition*, 141, 87-102.


# Re-use

This page was written by Kenny Smith with additional edits by Simon Kirby. All aspects of this work are licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
