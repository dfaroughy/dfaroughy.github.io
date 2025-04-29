---
order: 1
title: "Flow-based Generative Modeling of Particle-Clouds with Multimodal Stochastic Bridges"
collection: publications
category: ml_papers
date: 2025-05-01
excerpt: 'In this paper, we present a novel multimodal generative model for particle-clouds with continuous and discrete features. Our method combines flow-matching for the continuous modality with a Multivariate Random Telegraph process for the discrete modality. Our generative model achieves state-of-the-art performance on CMS open data.'
venue: 'Preprint'
paperurl: 'https://arxiv.org/pdf/2412.10504'
---

abstract
===
In many real-world scenarios, data is *hybrid* — i.e. described by continuous and discrete features. At high-energy accelerators like the LHC, jet constituents exhibit discrete properties such as electric charge, flavor and other quantum numbers. In this paper, we present a novel generative model for discrete features based on continuous-time Markov jump processes. By combining our approach with well-known dynamics for continuous features, such as diffusion or flow-matching, we can effectively model hybrid data within a unified framework. We apply our method to particle-clouds incorporating kinematic data, particle-id, and charge information. We demonstrate the effectiveness of our approach on the CMS open data {\tt AspenOpenJets} datasets.