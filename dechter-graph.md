Algorithms for Reasoning with Probabilistic Graphical Models
INTRODUCTORY

#Summary

The course will cover the primary exact and approximate algorithms for
reasoning with Probabilistic Graphical models (e.g., Bayesian and Markov
networks, influence diagrams, and Markov decision processes). I will present
inference-based, message-passing schemes (e.g., variable-elimination,) and
search-based, conditioning schemes (e.g., cycle-cutset conditioning and AND/OR
search). Each class possesses distinguished characteristics and in particular
has different time vs. space behavior. I will emphasize the dependence of both
schemes on few graph parameters such as the treewidth, cycle-cutset, and (the
pseudo-tree) height. I will start from exact algorithms and will move to
approximate schemes that are anytime, including weighted mini-bucket schemes
with cost-shifting.

#Syllabus

  * Introduction to graphical models; queries (i.e., MAP, Partition function,
    Marginals and Marginal Map) and algorithms (Inference and search).
  * Inference algorithms: Bucket-elimination and tree-clustering schemes,
  * Bounded inference: mini-bucket and weighted mini-buckets, belief
    propagation schemes (BP and IJGP), cost-shifting schemes.
  * AND/OR search spaces for graphical models, AND/OR Branch and Bound for
    combinatorial optimization (MAP/MPE).
  * Generating heuristics using mini-bucket elimination with tightening by
    cost-shifting tightening. (e.g., weighted Mini-bucket with moment matching)
  * Marginal Map by AND/OR search
  * Sampling: Cutset-sampling, SampleSearch and AND/OR sampling (as time
    permits)

#1 Models

#2 Inference

- p26 when the dual graph is a tree
- the goal of conditioning is to arrive at a tree
- p50 optimal varaiable assignment rather than just the opt value
- width of a variable: number of archs downwards from it?
- p61 trading memory for time
