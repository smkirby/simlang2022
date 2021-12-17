---
title: Reading 7
description: Hierarchical learning
---

Up until this point all the models we've looked at have treated a learner's prior biases as given and fixed: learners come to the learning task with some bias which, in conjunction with the data they are exposed to, shapes what they learn. But we've been a bit vague about where those prior biases come from. One possibility is that the priors reflect very broad domain-general principles that are likely to shape learning in many domains, including in language - for instance, the simplicity-based prior you covered last week is quite easy to motivate as an instance of a general preference in learning for simple explanations for the data you encounter. Another possibility, that we'll explore in the last couple of weeks of the course, is that priors *evolve*: maybe the expectations you bring to the learning task reflect innate, domain-specific constraints on the kinds of linguistic systems you expect to learn which have evolved through natural selection. But we've also seen several places where it seems like priors themselves might be learned, or at least might change over time: when we were looking at word learning and frequency learning models in weeks 3-4 we discussed the possibility that adults and children might have different expectations about how linguistic systems work, and one natural explanation for those differences is that your linguistic experiences shape your expectation about how linguistic systems work and therefore shape the prior that you bring to subsequent learning tasks (including, for example, an artificial word- or language-learning experiment).

This week we'll take a look at hierarchical learning models, where the inductive biases that shape learning are themselves learned - these models provide a natural way of modelling this process where you learn about higher-order properties of the data you encounter, and those developing expectations shape subsequent learning. In the lecture and lab we'll work with the simplest hierarchical model I could come up with, based on the frequency-learning model you are already familiar with from earlier in teh course. You'll recall that in that model learners were learning the frequency distribution over two variants, captured by the probability one of those variants, *θ*. The shape of the prior the learners use was determined by a parameter *α* - when *α* was small (less than 1) you have learners who expect very regular, non-variable distributions (*θ* should be low or high, but not around 0.5), whereas when *α* was large (greater than 1) you had learners who expect high variability (*θ* should be around 0.5). You might have wondered where this *α* parameter comes from - why would learners expect low or high variability? This week we're going to look at a simple model where the *α* parameter is learned; i.e. depending on their experiences, learners can learn to expect low or high variability.

Hierarchical learning models work in the same way as all the models you have seen so far - they just involve applying Bayes rule to learn higher-level properties of the data (so in the model we will look at in the labs, we are learning *α* rather than *θ*). But because they involve two levels of inference (learning the lower-level properties of the data and the higher-level properties) they are relatively complex, which makes it hard to find the ideal introductory reading. You therefore have some options! Try to read at least one of the following papers (before or after the lecture is fine):
- If you don't want any additional technical details on hierarchical models (beyond what's in the lecture and lab), then read [Smith et al. (2002)](https://discovered.ed.ac.uk/permalink/f/1s15qcp/TN_cdi_gale_infotracacademiconefile_A83520403) - this is a very cool experimental paper by Linda Smith and colleagues showing how the shape bias in word learning is itself learned.
- If you want a short summary of the idea behind hierarchical models, read section 3 of [Perfors et al. (2011)](https://cocosci.princeton.edu/tom/papers/LabPublications/BayesCogDev.pdf), which gives some of the intuitions behind hierarchical models without going into any of the modelling details.
- If you want a more concrete example, but with most of the technicalities hidden, read [Perfors et al. (2010)](https://discovered.ed.ac.uk/permalink/f/1s15qcp/TN_cdi_proquest_miscellaneous_733914212), which applies various hierarchical models to learning of verb subcategorization frames. The model we'll use in labs is a simplified version of the model they describe in Figure 1(a) in that paper.
- If you are happy with a fairly condensed explanation and a bit more mathematical notation, read [Kemp et al. (2007)](https://web.mit.edu/cocosci/Papers/devsci07_kempetal.pdf) - again, the model we'll be working with is a simplification of the model in Figure 1(a) in that paper.
Just remember, the actual model we'll be working with is pretty simple, and certainly simpler than the models in the papers above, so don't be intimidated by the reading!

# References

Kemp, C., Perfors, A. & Tenenbaum, J. B. (2007). Learning overhypotheses with hierarchical Bayesian models. *Developmental Science, 10*, 307–321.

Perfors, A., Tenenbaum, J. B., & Wonnacott, E. (2010). Variability, negative evidence, and the acquisition of verb argument constructions. *Journal of Child Language, 37*, 607-642.

Perfors, A., Tenenbaum, J. B., Griffiths, T. L., & Xu, F.. A tutorial introduction to Bayesian models of cognitive development. *Cognition, 120*, 302–321.

Smith, L.B., Jones, S.S., Landau, B., Gershkoff-Stowe, L., & Samuelson, L. (2002). Object name learning provides on-the- job training for attention. *Psychological Science, 13*, 13– 19.


# Re-use

This page was written by Kenny Smith. All aspects of this work are licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
