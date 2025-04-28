---
title: "Fast Particle Cloud Generation with Flow-Matching and Diffusion"
collection: publications
category: ml_papers
venue: The European Physical Journal C  
date: 2023-09-29
excerpt: In this paper we introduce permutation-equivariant Flow-Matching and Diffusion models for particle-cloud generation. The porposed architecture, which is a variant of deep-sets, achieves state-of-the-art results at the level of the much heavier transformer-based arthcitectures whilst
maintaining a muche faster generation speed.
paperurl: 'https://arxiv.org/pdf/2310.00049'
keywords: 'Generative Ai, flow-matching, diffusion, point-clouds'
---

abstract
===
Jets at the LHC, typically consisting of a large
number of highly correlated particles, are a fascinating
laboratory for deep generative modeling. In this paper,
we present two novel methods that generate LHC jets
as point clouds efficiently and accurately. We introduce
EPiC-JeDi, which combines score-matching diffusion
models with the Equivariant Point Cloud (EPiC) architecture based on the deep sets framework. This model offers a much faster alternative to previous transformer-based
diffusion models without reducing the quality of the generated jets. In addition, we introduce EPiC-FM, the first permutation equivariant continuous normalizing flow
(CNF) for particle cloud generation. This model is trained
with flow-matching, a scalable and easy-to-train objective
based on optimal transport that directly regresses the
vector fields connecting the Gaussian noise prior to the
data distribution. Our experiments demonstrate that
EPiC-JeDi and EPiC-FM both achieve state-of-the-art
performance on the top-quark JetNet datasets whilst
maintaining fast generation speed. Most notably, we find
that the EPiC-FM model consistently outperforms all the
other generative models considered here across every
metric. Finally, we also introduce two new particle cloud
performance metrics: the first based on the Kullback-Leibler divergence between feature distributions, the second is the negative log-posterior of a multi-model
ParticleNet classifier.