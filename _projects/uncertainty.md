---
layout: page
title: Modelling uncertainty
description: Uncertainty quantification and propagation. 
img: assets/img/uncertainty2.jpg
importance: 3
category: work
related_publications: true
---

We have developed a stream of pioneering work in the area of inference in Gaussian process (GP) models, ranging from regression, classification and multi-task problems to generic inference with black-box likelihoods. We have published this work at the very top ML venues. Our techniques are mainly underpinned by variational inference principles (optimizing rather than integrating). These efforts have been materialized recently in the development of one of the most flexible and scalable methods for inference in GP models {% cite rossi2021sparse %}, which uses stochastic gradient Hamiltonian Monte Carlo (SGHMC) along with variational inference techniques. New directions pursue the generalization of such techniques to time-evolving GPs and our most recent work on Gaussian process state-space models that has been published at ICML {% cite fan2023free %}.

 
More generally, we aim to address other problems in inference in graphical models (not necessarily using GP priors), and, e.g., understanding the theoretical properties of neural networks in frameworks such as state-space models {% cite bishop2023recurrent }. Perhaps more importantly, when considering uncertainty in the graphical model itself (i.e., how to model distributions over directed acyclic graphs and how to estimate posteriors over them). This will have crucial implications across many areas, especially, in causality research, see, e.g., VDESP {% cite bonilla2024variational %} and ProjDAG {% cite thompson2024prodag %}.
 

## Recent Developments 

### Inference in Gaussian Process Models
<ul>
    <li> Bayesian scalable GPs {% cite rossi2021sparse %} </li>
    <li> Inference in GP state-space models {% cite fan2023free %} </li>
</ul>

### Bayesian Approaches to Directed Acyclic Graph (DAG) Estimation and Graph Neural Networks
<ul>
    <li>Bayesian DAG estimation via permutation-based distributions {% cite bonilla2024variational %} </li>
    <li> Bayesian DAG estimation via Projection-induced distributions {% cite thompson2024prodag %} </li>
    <li> Bayesian Granger Causality {% cite zhao2024bayesian %}</li>
    <li> Variational graph convolutional networks {% cite elinas2020variational %}</li>
</ul>





