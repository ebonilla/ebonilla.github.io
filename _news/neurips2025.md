---
layout: post
title: 3 x papers at NeurIPS 2025
date: 2026-08-05 03:00:00+1000
inline: false
related_posts: false
---

We have 3 papers published at NeurIPS 2025: 

<ul>
    <li><a href="https://proceedings.neurips.cc/paper_files/paper/2025/hash/ee42c13f231836e914930925f950fc62-Abstract-Conference.html">ProDAG: Projected Variational Inference for Directed Acyclic Graphs</a></li>
    <li><a href="https://proceedings.neurips.cc/paper_files/paper/2025/hash/2f5fb82b8b593c548ed538a8d336d800-Abstract-Conference.html">Thompson Sampling in Function Spaces via Neural Operators</a></li>
    <li><a href="https://proceedings.neurips.cc/paper_files/paper/2025/hash/7c180af017258d239bac6248d1eb26ac-Abstract-Conference.html">Amortized Active Generation of Pareto Sets</a></li>    
</ul>

---
### ProDAG: Projected Variational Inference for Directed Acyclic Graphs
[NeurIPS 2025](https://proceedings.neurips.cc/paper_files/paper/2025/hash/ee42c13f231836e914930925f950fc62-Abstract-Conference.html)

When learning cause-and-effect maps from data (directed acyclic graphs, or DAGs), most methods just spit out one "best guess" map without saying how confident they are. This paper introduces a way to quantify that uncertainty properly, using a mathematical trick that reliably projects any distribution onto the space of valid, acyclic cause-and-effect maps. The result, ProDAG, is more accurate than prior methods and gives trustworthy confidence estimates alongside its predictions.


### Amortized Active Generation of Pareto Sets
[NeurIPS 2025](https://proceedings.neurips.cc/paper_files/paper/2025/hash/7c180af017258d239bac6248d1eb26ac-Abstract-Conference.html)

Many real design problems involve trade-offs between competing goals (e.g., a drug that's both effective and low-toxicity), where there's no single "best" answer, only a range of good compromises (the Pareto front). This paper presents a method, A-GPS, that trains a generative AI model to produce these trade-off options directly and can be steered afterward toward a user's specific preferences without retraining. Tested on synthetic problems and protein design, it finds strong sets of options with fewer costly evaluations.


### Thompson Sampling in Function Spaces via Neural Operators
[NeurIPS 2025](https://proceedings.neurips.cc/paper_files/paper/2025/hash/2f5fb82b8b593c548ed538a8d336d800-Abstract-Conference.html)

Some optimization problems involve tuning an entire simulated process, like a physics simulation, rather than just a few numbers, and running the simulation is expensive. This paper adapts a classic decision-making strategy (Thompson sampling) to this setting by using "neural operators", fast AI models that learn to mimic expensive simulators, as stand-ins for uncertainty about what the simulator would produce. The approach finds good designs for physical systems (governed by complex equations) using far fewer costly simulator runs.
