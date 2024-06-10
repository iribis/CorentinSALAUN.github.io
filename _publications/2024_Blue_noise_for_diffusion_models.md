---
title: "Blue noise for diffusion models"
authors: <p><a href="https://xchhuang.github.io/">Xingchang Huang</a>, <a href="https://iribis.github.io/">Corentin Salaün</a>, <a href="https://research.google/people/cristina-nader-vasconcelos/">Cristina Vasconcelos</a>, <a href="https://people.mpi-inf.mpg.de/~theobalt/">Christian Theobalt</a>, <a href="https://www.cl.cam.ac.uk/~aco41/">Cengiz Öztireli</a>, <a href="https://people.mpi-inf.mpg.de/~gsingh/">Gurprit Singh</a></p>
collection: publications
permalink: /publication/2024_Blue_noise_for_diffusion_models
excerpt: ''
date: 2024-07-28
venue: 'SIGGRAPH 2024 Conference Papers'
conference: 'ACM Siggraph 2024 (Conference track)'
citation: 'Huang, Xingchang. (2024). "Blue noise for diffusion models" <i>SIGGRAPH 2024 Conference Papers</i>.'

header:
  teaser: "http://iribis.github.io/files/Blue_noise_for_diffusion_models/teaser.png"
  thumbnail: "http://iribis.github.io/files/Blue_noise_for_diffusion_models/thumbnail.png"
---

![Teaser](http://iribis.github.io/files/Blue_noise_for_diffusion_models/teaser.png)

### Abstract

Most of the existing diffusion models use Gaussian noise for training and sampling across all time steps, which may not optimally account for the frequency contents reconstructed by the denoising network. Despite the diverse applications of correlated noise in computer graphics, its potential for improving the training process has been underexplored. In this paper, we introduce a novel and general class of diffusion models taking correlated noise within and across images into account. More specifically, we propose a time-varying noise model to incorporate correlated noise into the training process, as well as a method for fast generation of correlated noise mask. Our model is built upon deterministic diffusion models and utilizes blue noise to help improve the generation quality compared to using Gaussian white (random) noise only. Further, our framework allows introducing correlation across images within a single mini-batch to improve gradient flow. We perform both qualitative and quantitative evaluations on a variety of datasets using our method, achieving improvements on different tasks over existing deterministic diffusion models in terms of FID metric.

### Downloads and links
- <img width="20px" src="http://iribis.github.io/assets/fonts/file-pdf-solid.svg"> [Paper](http://iribis.github.io/files/Blue_noise_for_diffusion_models/paper.pdf)<br />
- <img width="20px" src="http://iribis.github.io/assets/fonts/file-pdf-solid.svg"> [Supplementals Document](http://iribis.github.io/files/Blue_noise_for_diffusion_models/supplemental.pdf)<br />
- <i class="fas fa-fw fa-link" aria-hidden="true"></i> [Supplementals](https://xchhuang.github.io/bndm/)<br />
