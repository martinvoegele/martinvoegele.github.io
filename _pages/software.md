---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

Most of the code I write as a computational scientist is one-off analysis code, mostly in Python. Whenever I think a method could be useful to others, I try to share it with the scientific community.
You can find my open-source contributions on <a href="https://github.com/martinvoegele">my GitHub profile</a>.
Here I highlight some of the bigger projects that I particularly care about.


## PENSA
**Toolbox for exploratory analysis and comparison of structural ensembles of proteins.**

(developed at Stanford University)

Molecular simulations enable the study of proteins and other biomolecules and their dynamics on an atomistic scale. The large amount of data produced for ever larger and more complex systems often makes it difficult to find the meaningful patterns for the respective system. While most available analysis tools provide methods to analyze one simulation at a time, many common research pursuits involve analysis across several simulations and finding significant differences between similar conditions or setups.

PENSA focuses on exploratory analysis and comparison of protein structural ensembles such as those from molecular dynamics simulations. Users can compare two conditions via the relative entropy of their features and visualize deviations on a reference structure. It also implements principal component analysis (PCs) and clustering across several ensembles and allows writing out the resulting principal components and clusters as trajectories. 
This method can speed up the discovery of molecular mechanisms that usually take many person-hours to identify.

<a href="https://github.com/drorlab/pensa">View it on GitHub.</a>


## ATOM3D 
**Benchmark suite for machine learning on three-dimensional molecular structure.**

(developed at Stanford University with Raphael Townshend, Patricia Suriana, Alexander Derry and others)

We assembled eight datasets specifically designed to provide a benchmark for machine learning methods which operate on 3D molecular structure, and represent a variety of important structural, functional, and engineering tasks. All datasets are provided in a standardized format along with corresponding processing code and dataloaders for common machine learning frameworks (PyTorch and TensorFlow). ATOM3D is designed to be a living database, where datasets are updated and tasks are added as the field progresses.

Check it out on <a href="https://www.atom3d.ai/">atom3d.ai</a> or on its <a href="https://github.com/drorlab/atom3d">GitHub page</a>.


## Binless WHAM
**Implementation of the binless weighted histogram analysis method for statistical reweighting of biased simulations.**

(developed at the Max Planck Institute of Biophysics with Alfredo Jost-López, Lukas Stelzl and Gerhard Hummer)

<a href="https://github.com/bio-phys/binless-wham">View it on GitHub.</a>


## MemDiff
**Corrections for diffusion coefficients from membrane simulations.**

(developed at the Max Planck Institute of Biophysics)

Lateral diffusion cefficients in membrane simulations with periodic boundary conditions are subject to substantial hydrodynamic finite-size effects. MemDiff is an  implementation of the correction formulas to obtain the unperturbed value from the values calculated in the simulation.

<a href="https://github.com/bio-phys/memdiff">View it on GitHub.</a>
