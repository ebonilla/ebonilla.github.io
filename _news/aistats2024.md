---
layout: post
title: Contextual DAGs at AISTATS 2024
date: 2024-06-25 09:30:00-0400
inline: false
related_posts: false
---

<a href="https://ryan-thompson.github.io">Ryan Thompson</a> presented our paper on  <a href="https://proceedings.mlr.press/v238/thompson24a.html">Contextual Directed Acyclic Graphs</a> at AISTATS 2024.

---

In this paper we estimate directed acyclic graphs (DAGs) from observational data where the DAG structure can be different for distinct individuals based on _contextual features_. The significance of DAG estimation in causal discovery is well known and documented but here we are taking it one step further by allowing each individual to have a (potentially) different DAG. This setting has many  applications (e.g., in personalized medicine) and, indeed, I think it is more realistic than estimating a DAG for the entire population. 

The paper has some neat mathematical tricks :sparkles: that allowed us to develop a fast and scalable algorithm, given the complexity of having neural networks to map contextual features into a DAG. We also provide a convergence guarantee and some cool experiments, including the analysis of drug consumption. 


 