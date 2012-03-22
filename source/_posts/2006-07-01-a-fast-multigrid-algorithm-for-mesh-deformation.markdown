---
layout: post
title: "A Fast Multigrid Algorithm for Mesh Deformation"
comments: false
categories: publications
abstract: "In this paper, we present a multigrid technique for efficiently deforming large surface and volume meshes. We show that a previous least-squares formulation for distortion minimization reduces to a Laplacian system on a general graph structure for which we derive an analytic expression. We then describe an efficient multigrid algorithm for solving the relevant equations. Here we develop novel prolongation and restriction operators used in the multigrid cycles. Combined with a simple but effective graph coarsening strategy, our algorithm can outperform other multigrid solvers and the factorization stage of direct solvers in both time and memory costs for large meshes. It is demonstrated that our solver can trade off accuracy for speed to achieve greater interactivity, which is attractive for manipulating large meshes. Our multigrid solver is particularly well suited for a mesh editing environment which does not permit extensive precomputation. Experimental evidence of these advantages is provided on a number of meshes with a wide range of size. With our mesh deformation solver, we also successfully demonstrate that visually appealing mesh animations can be generated from both motion capture data and a single base mesh even when they are inconsistent."
tags: [multigrid, mesh, deformation, animation]
authors: [Lin Shi, Yizhou Yu, Nathan Bell, Wei-Wen Feng]
publication: "SIGGRAPH 2006 (ACM Transactions on Graphics, Vol. 24, No. 3)"
teaser: media/2006-07-SIGGRAPH-Multigrid/thumbnail.jpg
---

{% include publication.html %}

### Downloads

 * [Paper (PDF)]({{ site.root }}media/2006-07-SIGGRAPH/ShYiBeFe2006.pdf)
 * [Video (AVI)]({{ site.root }}media/2006-07-SIGGRAPH/FastMultigridMesh.avi)

### External Links

 * [ACM Digital Library](http://dl.acm.org/citation.cfm?id=1142001)

