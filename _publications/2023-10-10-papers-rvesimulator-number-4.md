---
title: "rvesimulator: An Automated Representative Volume Element Simulator for Data-Driven Material Discovery"
collection: publications
category: conferences
permalink: /publication/2023-10-rvesimulator
excerpt: "rvesimulator is a Python-Abaqus framework for automating RVE simulations to support large-scale material data generation."
date: 2023-10-27
venue: "AI4Mat Workshop (NeurIPS 2023)"
paperurl: "https://openreview.net/forum?id=511z1DGjPi"
bibtexurl: "https://openreview.net/forum?id=511z1DGjPi&bibtex"
citation: "Yi, J. & Bessa, M. (2023). “rvesimulator: An automated representative volume element simulator for data-driven material discovery.” AI4Mat 2023 Workshop, NeurIPS."
---


The rvesimulator aims to provide a user-friendly, automated Python-based framework conducting Representative Volume Element (RVE) simulation via powerful Finite Element Method (FEM) software Abaqus. By utilizing this repository, large amount of reliable FEM data-set generation is possible with RVEs encompassing materials from elastic to plastic composites. rvesimulator provides: (1) a cross-platform function to run arbitrary Python-Abaqus script without graphical user interface (GUI), it offers users a convenience way to run their unique scripts; (2) Python-Abaqus scripts to simulate RVE with different design of experiments including various micro-structures, material laws, and loading; (3) benchmarks of running prevalent RVEs covering elastic, hyper-elastic, plastic materials are provided, which illustrates the general pipeline (preprocess, execution, and postprocess) of the developed framework. By sharing the developing framework, we are aiming to reduce the labor-intensive process of generating massive of simulations data for new materials and structure discovery. Therefore, it facilitates the application and development of machine learning method for new material discovery.
