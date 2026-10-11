---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<p><a href="{{ base_path }}/files/Abbasi_Hamid_resume_engineering.pdf" class="btn btn--primary" target="_blank"><i class="fa fa-download"></i> Download Full Resume (PDF)</a></p>

## Education

* **Ph.D. in Chemical Engineering**, University of Manchester *(Jan 2022 – Jul 2025)*
  * *Thesis:* Multiscale model of solid oxide fuel cells ([GitHub /SOFC-project](https://github.com/HamidAbbasi-R/SOFC-project))
  * *Award:* Recipient of the University of Manchester [President's Doctoral Scholarship](https://www.manchester.ac.uk/study/postgraduate-research/funding/presidents-doctoral-scholar-award/)
* **M.Sc. in Mechanical Engineering**, Iran University of Science and Technology *(Sep 2017 – Jun 2020)*
  * *GPA:* 3.88 / 4.0 (Ranked 1<sup>st</sup> among 2020 graduates)
  * *Thesis:* Numerical modeling of transient turbulent airflow inside air compressors
* **B.Sc. in Mechanical Engineering**, Shiraz University *(Sep 2013 – Jun 2017)*
  * *GPA:* 3.55 / 4.0 (Top 10% of graduating cohort)

---

## Work Experience

* **Research Associate**, Imperial College London *(July 2025 – Present)*
  * **Project CASTLE**: Architected scalable Lagrangian contrail-cirrus atmospheric interactions in C++ and Python using hybrid parallelization (MPI/OpenMP) on HPC clusters.
  * Developed stochastic models for cirrus cloud formation linked to probabilistic gravity-wave parameterizations.
  * **Project CLAMP**: Optimized Lagrangian plume-scale contrail dynamics using advanced vectorization and Numba compilation.
* **Graduate Teaching Assistant**, University of Manchester *(Sep 2022 – Jan 2024)*
  * Process Design (P&ID construction)
  * Engineering Mathematics 2 & 3 (Linear algebra, ODEs & PDEs, Multivariable Calculus, Complex Analysis)
  * Fundamentals of Thermodynamics
* **Lecturer**, Wanhua Chemical Group *(Sep 2023 – Jan 2024)*
  * Reaction Systems: Stochastic time-dependent reaction dynamics & Monte Carlo simulations (Gillespie algorithm).
* **Graduate Teaching Assistant**, Iran University of Science and Technology *(Sep 2018 – Jan 2021)*
  * Optimization of Thermal Systems, Thermodynamics & CFD, Fluid Mechanics I & II.

---

## Technical Skills & Tools

* **Programming & Scientific Stack:** Python, C++, MATLAB, Fortran, LaTeX
* **Parallel & High-Performance Computing:** MPI, OpenMP, CUDA, Numba, mpi4py, RAPIDS (cuDF, cuML), Dask
* **Data Science & ML:** PyTorch, Physics-Informed ML (TBNN), Scikit-Learn, Pandas, Polars, Xarray
* **Engineering & Simulation Software:** COMSOL Multiphysics, ANSYS Fluent

---

## Certifications

* **NVIDIA Deep Learning Institute (DLI):**
  * Accelerating CUDA C++ Applications with Multiple GPUs
  * Fundamentals of Accelerated Computing with CUDA Python
  * Deep Learning & Transformer-Based Natural Language Processing
  * Accelerating End-to-End Data Science Workflows (RAPIDS)
* **HarvardX Professional Data Science:**
  * Probability, Inference and Modeling, Data Wrangling, Linear Regression, Machine Learning
* **University of Manchester at Harwell:**
  * Visualization and Quantification of Tomographic Datasets

---

## Publications & Research Output

Full publication profile with citations and metrics available on [Google Scholar](https://scholar.google.com/citations?user=uMCSKucAAAAJ&hl=en).

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
