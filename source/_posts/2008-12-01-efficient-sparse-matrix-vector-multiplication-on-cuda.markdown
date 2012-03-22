---
layout: post
title: "Efficient Sparse Matrix-Vector Multiplication on CUDA"
categories: publications
abstract:
  <p>The massive parallelism of graphics processing units (GPUs) offers tremendous performance in many
  high-performance computing applications. While dense linear algebra readily maps to such platforms,
  harnessing this potential for sparse matrix computations presents additional challenges. Given its role
  in iterative methods for solving sparse linear systems and eigenvalue problems, sparse matrix-vector
  multiplication (SpMV) is of singular importance in sparse linear algebra.</p>
  <p>In this paper we discuss data structures and algorithms for SpMV that are efficiently implemented
  on the CUDA platform for the fine-grained parallel architecture of the GPU. Given the memory-bound
  nature of SpMV, we emphasize memory bandwidth efficiency and compact storage formats. We consider
  a broad spectrum of sparse matrices, from those that are well-structured and regular to highly irregular
  matrices with large imbalances in the distribution of nonzeros per matrix row. We develop methods to
  exploit several common forms of matrix structure while offering alternatives which accommodate greater
  irregularity.</p>
  <p>On structured, grid-based matrices we achieve performance of 36 GFLOP/s in single precision and
  16 GFLOP/s in double precision on a GeForce GTX 280 GPU. For unstructured finite-element matrices,
  we observe performance in excess of 15 GFLOP/s and 10 GFLOP/s in single and double precision
  respectively. These results compare favorably to prior state-of-the-art studies of SpMV methods on
  conventional multicore processors. Our double precision SpMV performance is generally two and a half
  times that of a Cell BE with 8 SPEs and more than ten times greater than that of a quad-core Intel
  Clovertown system.</p>
tags: [sparse, matrix, GPU, CUDA, SpMV]
authors: [Nathan Bell, Michael Garland]
publication: "NVIDIA Technical Report NVR-2008-004, December 2008"
teaser: media/2008-12-NVR-SpMV/thumbnail.png
---

{% include publication.html %}

### Downloads

 * [Paper (PDF)]({{ site.root }}media/2008-12-NVR-SpMV/nvr-2008-004.pdf)
 * [BibTeX (TXT)]({{ site.root }}media/2008-12-NVR-SpMV/bibtex.txt)

### External Links

 * [NVIDIA Research](http://research.nvidia.com/publication/efficient-sparse-matrix-vector-multiplication-cuda)
 * [Source Code](http://code.google.com/p/cusp-library/downloads/list)

