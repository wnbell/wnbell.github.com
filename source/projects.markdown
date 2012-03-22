---
layout: default
title: Open Source Projects
projects:
 -
  name: Thrust
  link: http://thrust.github.com
  logo: Thrust.png
  text: "Thrust is a parallel algorithms library which resembles the C++ Standard Template Library (STL). Thrust's <b>high-level</b> interface greatly enhances developer <b>productivity</b> while enabling performance portability between GPUs and multicore CPUs.  <b>Interoperability</b> with established technologies (such as CUDA, TBB and OpenMP) facilitates integration with existing software.  Develop <b>high-performance</b> applications rapidly with Thrust!"
 -
  name: Cusp
  link: http://code.google.com/p/cusp-library/
  logo: Cusp.png
  text: "Cusp is a library for sparse linear algebra and graph computations on CUDA. Cusp provides a flexible, high-level interface for manipulating sparse matrices and solving sparse linear systems."
 -
  name: PyAMG
  link: http://code.google.com/p/pyamg/
  logo: PyAMG.png
  text: "PyAMG is a library of Algebraic Multigrid (AMG) solvers with a convenient Python interface."
 -
  name: PyDEC
  link: http://code.google.com/p/pydec/
  logo: PyDEC.png
  text: "PyDEC: A Python Library for Discretization of Exterior Calculus."
 -
  name: SciPy
  link: http://www.scipy.org
  logo: SciPy.png
  text: "SciPy is open-source software for mathematics, science, and engineering. The SciPy library is built to work with NumPy arrays, and provides many user-friendly and efficient numerical routines such as routines for numerical integration and optimization."
---

{% for project in page.projects %}
<div class="project">
  <a href={{ project.link }}>
      <img class="project_logo" alt="{{ project.name }} logo" title="{{ project.name }} site" src="{{ site.root }}media/logos/{{ project.logo }}" />
  </a>
  <div class="project_text">
    <p>{{ project.text }}</p>
  </div>
</div>
{% endfor %}

