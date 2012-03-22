---
layout: post
title: "Implementing Sparse Matrix-Vector Multiplication on Throughput-Oriented Processors"
categories: publications
abstract: "Sparse matrix-vector multiplication (SpMV) is of singular importance in sparse linear algebra. In contrast to the uniform regularity of dense linear algebra, sparse operations encounter a broad spectrum of matrices ranging from the regular to the highly irregular. Harnessing the tremendous potential of throughput-oriented processors for sparse operations requires that we expose substantial fine-grained parallelism and impose sufficient regularity on execution paths and memory access patterns. We explore SpMV methods that are well-suited to throughput-oriented architectures like the GPU and which exploit several common sparsity classes. The techniques we propose are efficient, successfully utilizing large percentages of peak bandwidth. Furthermore, they deliver excellent total throughput, averaging 16 GFLOP/s and 10 GFLOP/s in double precision for structured grid and unstructured mesh matrices, respectively, on a GeForce GTX 285. This is roughly 2.8 times the throughput previously achieved on Cell BE and more than 10 times that of a quad-core Intel Clovertown system."
tags: [sparse, matrix, GPU, throughput-oriented, SpMV]
authors: [Nathan Bell, Michael Garland]
publication: "Proc. Supercomputing '09, November 2009"
teaser: media/2009-11-SC-SpMV/thumbnail.png
---

{% include publication.html %}

### Downloads

 * [Paper (PDF)]({{ site.root }}media/2009-11-SC-SpMV/nvr-2008-004.pdf)

### External Links

 * [ACM Digital Library](http://dl.acm.org/citation.cfm?doid=1654059.1654078)
 * [NVIDIA Research](http://research.nvidia.com/content/implementing-sparse-matrix-vector-multiplication-throughput-oriented-processors)
 * [Source Code](http://code.google.com/p/cusp-library/downloads/list)

