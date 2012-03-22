---
layout: post
title: "Exposing Fine-Grained Parallelism in Algebraic Multigrid Methods"
categories: publications
abstract: "Algebraic multigrid methods for large, sparse linear systems are a necessity in many computational simulations, yet parallel algorithms for such solvers are generally decomposed into coarse-grained tasks suitable for distributed computers with traditional processing cores. However, accelerating multigrid on massively parallel throughput-oriented processors, such as the GPU, demands algorithms with abundant fine-grained parallelism. In this paper, we develop a parallel algebraic multigrid method which exposes substantial fine-grained parallelism in both the construction of the multigrid hierarchy as well as the cycling or solve stage. Our algorithms are expressed in terms of scalable parallel primitives that are efficiently implemented on the GPU. The resulting solver achieves an average speedup of over 2x in the setup phase and around 6x in the cycling phase when compared to a representative CPU implementation."
tags: [fine-grained parallelism, algebraic multigrid, AMG, GPU]
authors: [Nathan Bell, Steven Dalton, Luke Olson]
publication: "NVIDIA Technical Report NVR-2011-002, June 2011"
teaser: media/2011-06-NVR-AMG/thumbnail.png
---

{% include publication.html %}

### Downloads

 * [Paper (PDF)]({{ site.root }}media/2011-06-NVR-AMG/nvr-2011-002.pdf)
 * [BibTeX (TXT)]({{ site.root }}media/2011-06-NVR-AMG/bibtex.txt)

### External Links

 * [NVIDIA Research](http://research.nvidia.com/publication/exposing-fine-grained-parallelism-algebraic-multigrid-methods)
 * [Source Code](http://code.google.com/p/cusp-library/downloads/list)

