---
title: "Uncovering hidden new physics patterns in collider events using Bayesian probabilistic models"
collection: publications
category: ml_papers
date: 2022-09-15
venue: 'Proceedings of Science'
paperurl: 'https://pos.sissa.it/390/238/pdf'

---
Individual events at high-energy colliders like the LHC can be represented by a sequence of measurements, or ‘point clouds’. Starting from this generic data representation, we build a simple Bayesian probabilistic model for event measurements useful for unsupervised event classification in beyond the standard model (BSM) studies. In order to arrive to this model we assume that the event measurements are exchangeable (and apply De Finetti’s representation theorem), the data is tokenized, and measurements are generated from multiple ‘latent’ distributions (called themes). The resulting probabilistic model for collider events is a mixed-membership model known as Latent Dirichlet Allocation (LDA), a model extensively used in natural language processing applications. By training on mixed dijet samples of QCD and BSM, we demonstrate that a two-theme LDA model can learn to distinguish in (unlabelled) jet substructure data the hidden new physics patterns produced by a non-trivial BSM signature from a much larger QCD background.