---
title: Reading 9
description: Gene-culture co-evolution
---


Last week we saw how different strategies for picking the hypothesis from the posterior lead to different relationships between the prior bias and the stationary distribution. This is important since the stationary distribution is essentially the core of what linguistics is trying to explain: why languages look the way they do. The prior bias is what learners bring to the task of learning language before they've seen any linguistic data, and therefore can be thought of as what is *innate* about language learning. In this sense, the iterated learning model is an approach to understandign the relationship between innatenenss and language. If details of that model change that relationship, then they have potentially important implications for our theory of language.

This week we consider how language learning itself might change over time as a product of biological (rather than cultural) evolution. If we assume that learning language confers some degree of *fitness* (i.e. improved chances of passing on your genes to the next generation), and we assume that aspects of the way language is learned (such as the hypothesis selection strategy and the strength of the prior bias) are determined at least in part by the genes, then we can test different types of learner to see which ones are more likely to persist in a population subject to natural selection.

In the lab, we will be extending the model from last week to use the approach outlined in [Smith & Kirby (2008)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2607345/pdf/rstb20080145.pdf). We will start with a population of one type of learner and run iterated learning to derive the stationary distribution of languages. Then we will see how well that type of learner actually learns the languages from that stationary distribution. Next we will imagine a mutant learner who is also learning the languages from that same distribution. We will ask the simple question: is the mutant better or worse than the majority type of learner? If the mutant is better, then we can assume it has a chance of "invading" the population and eventually becoming the new majority type of learner. If it is worse then we can assume it will die out.

In the lecture, I summarise the results of [Thompson et al. (2016)](https://www.pnas.org/content/pnas/113/16/4530.full.pdf), which goes one step further and fully models the process of biological evolution, allowing mutations to arise naturally and looking at what the end state of gene-culture co-evolution is for language under different starting assumptions. (Fun fact: Bill Thompson was a student on this Simulating Language course, and started work on the model for this paper for his dissertation after the course - never having previously built a model!)

The conclusion from this modelling is straightforward:

1. We should expect MAP learners to evolve in the case of learned social behaviours.
2. We should expect strong innate biases to become weak in the case of behaviours transmitted in populations of MAP learners.

If we define linguistic nativism as the hypothesis that we are born with strongly constraining domain specific biases on the nature of language, then these models predict that linguistic nativism of this type cannot evolve.

However, note that this allows for two different types of nativism still: strongly constraining innate constraints could be domain general (i.e. not having evolved for language), and domain-specific innate constraints can still evolve, but we should expect them to take the form of weak biases on learning.


# References

Smith, K., & Kirby, S. (2008). Cultural evolution: implications for understanding the human language faculty and its evolution. *Philosophical Transactions of the Royal Society B*, 363, 3591-360.

Thompson, B., Kirby, S., & Smith, K. (2016). Culture shapes the evolution of cognition. *Proceedings of the National Academy of Science*, 113:16, 4530–4535.



# Re-use

This page was written by Simon Kirby. All aspects of this work are licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
