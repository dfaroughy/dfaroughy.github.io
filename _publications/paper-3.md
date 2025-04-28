---
title: "Aspen Open Jets: Unlocking LHC Data for Foundation Models in Particle Physics"
collection: publications
category: ml_papers
date: 2023-09-29
paperurl: 'https://arxiv.org/pdf/2412.10504'
---
Foundation models are deep learning models pre-trained on large amounts of data which are capable of generalizing to multiple datasets and/or downstream tasks. This work demonstrates how data collected by the CMS experiment at the Large Hadron Collider can be useful in pre-training foundation models for HEP. Specifically, we introduce the AspenOpenJets dataset, consisting of approximately 180M high-pT jets derived from CMS 2016 Open Data. We show how pre-training the OmniJet-alpha foundation model on AspenOpenJets improves performance on generative tasks with significant domain shift: generating boosted top and QCD jets from the simulated JetClass dataset. In addition to demonstrating the power of pre-training of a jet-based foundation model on actual proton-proton collision data, we provide the ML-ready derived AspenOpenJets dataset for further public use.