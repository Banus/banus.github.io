---
layout: page
title: CRISM Machine Learning Toolkit
description: A Machine Learning Toolkit for CRISM Image Analysis.
img:
importance: 2
category: PhD
---

In this project we demonstrate the utility of machine learning in two essential CRISM analysis tasks: nonlinear noise removal and mineral classification. We propose a simple yet effective hierarchical Bayesian model for estimating distributions of spectral patterns and extensively validate this model for mineral classification on several test images. We package implemented scripts, documentation illustrating use cases, and pixel-scale training data collected from dozens of well-characterized CRISM images into a new toolkit. We hope that this new toolkit will provide advanced and effective processing tools and improve planetary community's ability to map compositional units in remote sensing data quickly, accurately, and at scale.

**Datasets:**

The training datasets used in this study are publicly available on Zenodo ([dataset page](https://zenodo.org/records/13338091)):

- [Unratioed training dataset for bland pixels](https://zenodo.org/records/13338091/files/CRISM_bland_unratioed.mat?download=1)
- [Ratioed training dataset for mineral classes](https://zenodo.org/records/13338091/files/CRISM_labeled_pixels_ratioed.mat?download=1)
- [Training segmentation maps and average spectra](https://zenodo.org/records/13338091/files/CRISM_labeled_pixel_patterns.pdf?download=1)

The toolkit with a user friendly Python notebook, source codes, and documentation is hosted at [GitHub](https://github.com/Banus/crism_ml). To save space the training datasets are not included in the package and have to be downloaded from above links.

**Citation:**

Emanuele Plebani, Bethany L. Ehlmann, Ellen K. Leask, Valerie K. Fox, M. Murat Dundar, "A Machine Learning Toolkit for CRISM Image Analysis", Icarus, January 2022. DOI: https://doi.org/10.1016/j.icarus.2021.114849

**Acknowledgement:**

- The development of the machine learning algorithms in the toolkit was sponsored by the National Science Foundation (NSF) under Grant Number IIS-1252648 (CAREER). The content is solely the responsibility of the authors and does not necessarily represent the official views of NSF.

- Toolkit development and validation was sponsored by NASA under Grant Number 80NSSC19K1594.
