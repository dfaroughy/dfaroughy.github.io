---
title: "EPiC-ly Fast Particle Cloud Generation with Flow-Matching and Diffusion"
collection: publications
category: manuscripts
date: 2023-09-29
venue: 'Preprint'
slidesurl: ''
excerpt: 'Jets at the LHC, typically consisting of a large
number of highly correlated particles, are a fascinating
laboratory for deep generative modeling. In this paper,
we present two novel methods that generate LHC jets
as point clouds efficiently and accurately. We introduce
EPiC-JeDi, which combines score-matching diffusion
models with the Equivariant Point Cloud (EPiC) architecture based on the deep sets framework. This model offers
a much faster alternative to previous transformer-based
diffusion models without reducing the quality of the generated jets. In addition, we introduce EPiC-FM, the first
permutation equivariant continuous normalizing flow
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
performance metrics: the first based on the KullbackLeibler divergence between feature distributions, the
second is the negative log-posterior of a multi-model
ParticleNet classifier.'
paperurl: 'https://inspirehep.net/literature/1836854'
bibtexurl: ''
citation: 'Darius A. Faroughy. (2023). "EPiC-ly Fast Particle Cloud Generation with Flow-Matching and Diffusion." e-Print: 2310.00049 [hep-ph].'
---
