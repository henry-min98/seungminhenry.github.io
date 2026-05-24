---
layout: archive
permalink: /
author_profile: true
---

<section id="biography" markdown="1">
<h1>Biography</h1>

Seungmin (Henry) Lee is a Graduate Research Assistant under Dr. William F. Schneider in the Department of Chemical and Biomolecular Engineering at the University of Notre Dame, where he will receive his M.S. degree in August 2026. Previously, he was an Undergraduate Research Assistant under Dr. Rose Cersonsky at the University of Wisconsin–Madison (2022–2024).

At Notre Dame, he demonstrated that dealumination in H-CHA zeolites follows non-mean-field behavior through **nonlinear regression**, and provided mechanistic explanation by implementing **kinetic Monte Carlo simulations** to capture spatial resolution effects. 

He also implemented Machine Learning Interatomic Potentials (**MLIP**) using REANN, which is a **CUDA** and **PyTorch**-based framework, to accelerate **molecular dynamics** simulations, achieving approximately 98% reduction in computational wall time.

He evaluated machine learning model predictabilities and contributed results published in ACS Omega. He specializes in **machine learning** applications in chemistry, **molecular simulation**, and **chemical process engineering**.

<div style="display: flex; gap: 40px; margin-top: 20px;">
<div style="flex: 1;" markdown="1">

## Interests
- Computational chemistry & physics
- Numerical optimization and solvers
- Statistical modeling
- Molecular dynamics
- Process (Chemical) Engineering
- Process optimization

</div>
<div style="flex: 1;" markdown="1">

## Education

- **M.S. in Chemical and Biomolecular Engineering**<br>
  University of Notre Dame, 2026<br>
  <img src="/images/notredame.png" alt="University of Notre Dame" style="width: 100%; margin-top: 6px;">

- **B.S. in Chemical Engineering**<br>
  University of Wisconsin–Madison, 2024<br>
  <img src="/images/madison.png" alt="University of Wisconsin-Madison" style="width: 100%; margin-top: 6px;">

</div>
</div>

</section>

---

<section id="experiences" markdown="1">
<h1>Experiences</h1>

### Graduate Research Assistant & Teaching Assistant

University of Notre Dame

Aug. 2024 – Expected Aug. 2026

- Conducted research on zeolite dealumination kinetics under Dr. William F. Schneider, developing **kinetic Monte Carlo** simulations and applying **Bayesian Optimization with Gaussian Process** regression for parameter estimation
- Implemented **Machine Learning Interatomic Potentials (MLIP)** using REANN (**PyTorch/CUDA**) to accelerate molecular dynamics simulations of N₂ dissociation on Pd surfaces, achieving ~98% reduction in computational wall time
- Served as Teaching Assistant for Graduate Reaction Engineering and Thermodynamics, holding office hours, grading assignments, and supporting student learning in Chemical Engineering

---

### Undergraduate Research Assistant

University of Wisconsin–Madison

Dec. 2022 – May 2024

- Conducted research under Dr. Rose Cersonsky on **machine learning** prediction of photonic band gap (PBG) properties in 3D photonic crystals
- Engineered structural feature representations using OneHotEncoder and benchmarked multiple supervised learning classifiers (Random Forest, SVC, Naïve Bayes) on 1,000+ crystal datasets
- Contributed findings to a peer-reviewed publication in *ACS Omega* (2026)

---

### Undergraduate Teaching Assistant & Course Grader

University of Wisconsin–Madison

Jan. 2022 – May 2024

- Assisted course instruction for undergraduate chemical engineering courses, providing academic support through office hours and exam review sessions
- Graded assignments and exams with detailed written feedback to reinforce student understanding of core concepts

</section>

---

<section id="projects" markdown="1">
<h1>Projects</h1>

## Explanation of Non-Mean-Field Behavior of Dealumination in H-CHA
*August 2025 – August 2026 · University of Notre Dame · Advisor: Dr. William F. Schneider*

<img src="/images/project1.png" alt="Dealumination project" style="width:100%; margin: 10px 0 16px 0; border-radius: 8px;">

- Identified fundamental limitations of global 2nd-order mean-field kinetic models in describing dealumination using **non-linear regression** across varying aluminum concentrations in H-CHA zeolites, establishing evidence for spatially-dependent reaction mechanisms
- Developed a **kinetic Monte Carlo (kMC)** simulation framework to resolve site-level spatial heterogeneity in dealumination kinetics, providing mechanistic insight beyond continuum approximations
- **Optimized** kinetic parameters via **Bayesian Optimization with Gaussian Process** surrogate modeling, enabling efficient exploration of high-dimensional parameter space and improving model–experiment agreement

---

## Relationship between N₂ Vibrational Excitation and Sticking Probability in N₂ Dissociation on Palladium Surface
*August 2024 – August 2025 · University of Notre Dame · Advisor: Dr. William F. Schneider*

<img src="/images/project2.png" alt="MLIP REANN project" style="width:100%; margin: 10px 0 16px 0; border-radius: 8px;">

- Deployed **REANN (Recursively Embedded Atomic Neural Network)**, a **CUDA/PyTorch**-based **Machine Learning Interatomic Potential (MLIP)**, to replace computationally prohibitive **ab initio molecular dynamics (AIMD)** for N₂/Pd surface simulations
- Achieved ~98% reduction in computational wall time, enabling statistically robust datasets of 10,000 MD trajectories per vibrational state (v = 0–4), which was a scale inaccessible to conventional AIMD
- Quantified a Boltzmann exponential relationship between N₂ vibrational excitation state and surface sticking probability, providing a predictive framework linking plasma excitation energy to catalytic dissociation efficiency

---

## Photonic Band Gap Prediction in Crystals using Machine Learning
*December 2022 – May 2024 · University of Wisconsin–Madison · Advisor: Dr. Rose Cersonsky*

<img src="/images/project3.png" alt="Photonic band gap ML project" style="width:100%; margin: 10px 0 16px 0; border-radius: 8px;">

- Engineered structural feature representations of 3D photonic crystals using OneHotEncoder, enabling compatibility of categorical crystallographic data with **supervised learning** pipelines
- Benchmarked Random Forest, Support Vector Classifier (SVC) with varying kernel degrees, and Naïve Bayes models on 1,000+ photonic band gap (PBG) datasets, identifying the highest-performing classifier for PBG prediction
- Interpreted model outputs in terms of physically meaningful structural descriptors, with results contributing to a peer-reviewed publication in *ACS Omega* (2026)

---

## Solvent-Targeted Recovery and Precipitation (STRAP) Process Design
*Spring 2024 · University of Wisconsin–Madison*

<img src="/images/project4.png" alt="STRAP process design" style="width:100%; margin: 10px 0 16px 0; border-radius: 8px;">

- Designed and simulated a full-scale solvent recovery and polyethylene (PE) purification process in **Aspen Plus**, integrating multi-unit operations including separation, precipitation, and solvent recycle loops
- Performed rigorous mass balance and economic feasibility analysis in **Microsoft-Excel**, quantifying production costs, solvent consumption, and revenue projections under varying operating scenarios
- Delivered a process design achieving 500 kg/hr of recycled PE at less than 10 ppm residual solvent, with sensitivity analysis identifying critical operating parameters governing yield and solvent removal efficiency

</section>

---

<section id="publications" markdown="1">
<h1>Publications</h1>

## Journal Articles

---

## [Data-Driven Design Rules for Three-Dimensional Photonic Crystals](https://pubs.acs.org/doi/pdf/10.1021/acsomega.6c00256)

Rose K. Cersonsky, Saswat K. Nayak, and Seungmin H. Lee

*ACS Omega*, 2026

</section>

---

<section id="cv">
<h1>CV</h1>

[Download CV (PDF)](files/Seungmin_Lee_Resume.pdf)

<iframe src="files/Seungmin_Lee_Resume.pdf" width="100%" height="800px">
</iframe>

</section>