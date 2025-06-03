---
title: "POMsGibbsNet"
excerpt: "A deep learning framework for predicting polyoxometalate formation energies and stability using graph neural networks."
collection: opensource_projects
category: software
permalink: /opensource_projects/poms-gibbsnet
date: 2025-08-01
projecturl: 'https://gitlab.com/jbuils/poms-gibbsnet'
layout: single
author_profile: true

---

------ 

#### Project directory

[GitLab]('https://gitlab.com/jbuils/poms-gibbsnet')

### Project description

POMS-GibbsNet is a specialized deep learning framework designed to predict formation energies and thermodynamic stability of polyoxometalates (POMs) using graph neural networks. This tool bridges computational chemistry and machine learning to accelerate the discovery and design of novel POM structures.

### Features

* Graph-based representation of POM molecular structures
* Prediction of Gibbs free energies of formation
* Stability analysis across different pH and concentration conditions
* Structure-property relationship visualization
* Transfer learning capabilities from DFT-calculated datasets

### Methods

* Graph Neural Networks (GNNs) for molecular representation
* Message Passing Neural Networks for atomic interactions
* Attention mechanisms for capturing long-range interactions
* Ensemble learning for uncertainty quantification
* Active learning for efficient data acquisition

### Applications

* Materials discovery for energy storage
* Prediction of POM behavior in complex solutions
* Rational design of self-assembling POM structures
* Integration with POMSimulator for comprehensive modeling

### Technical Details
The framework is implemented in PyTorch and PyTorch Geometric, providing efficient GPU acceleration for training and inference. The codebase includes visualization tools for analyzing prediction results and model interpretability.