---
title: "Perceptual error optimization for Monte Carlo animation rendering"
authors: <p><a href="https://graphics.cg.uni-saarland.de/people/korac.html">Miša Korać</a>, <a href="https://iribis.github.io/">Corentin Salaün</a>, <a href="http://iliyan.com/">Iliyan Georgiev</a>, <a href="https://graphics.cg.uni-saarland.de/people/grittmann.html">Pascal Grittmann</a>, <a href="https://graphics.cg.uni-saarland.de/people/slusallek.html">Philipp Slusallek</a>, <a href="https://people.mpi-inf.mpg.de/~gsingh/">Gurprit Singh</a></p>
collection: publications
permalink: /publication/2023_Filtered_Sliced_Optimal_Transport
excerpt: ''
date: 2023-10-02
venue: 'SIGGRAPH Asia 2023 Conference Papers'
conference: 'ACM Siggraph asia 2023 (Conference track)'
citation: 'Korać, Miša. (2023). "Perceptual error optimization for Monte Carlo animation rendering" <i>SIGGRAPH Asia 2023 Conference Papers</i>.'

header:
  teaser: "http://iribis.github.io/files/Perceptual_error_optimization_for_Monte Carlo_animation_rendering/teaser.jpg"
  thumbnail: "http://iribis.github.io/files/Perceptual_error_optimization_for_Monte Carlo_animation_rendering/thumbnail.jpg"
---

![Teaser](http://iribis.github.io/files/Perceptual_error_optimization_for_Monte Carlo_animation_rendering/teaser.jpg)

### Abstract

Independently estimating pixel values in Monte Carlo rendering results in a perceptually sub-optimal white-noise distribution of error in image space. Recent works have shown that perceptual fidelity can be improved significantly by distributing pixel error as blue noise instead. Most such works have focused on static images, ignoring the temporal perceptual effects of animation display. We extend prior formulations to simultaneously consider the spatial and temporal domains, and perform an analysis to motivate a perceptually better spatio-temporal error distribution. We then propose a practical error optimization algorithm for spatio-temporal rendering and demonstrate its effectiveness in various configurations.


### Downloads and links
- <img width="20px" src="http://iribis.github.io/assets/fonts/file-pdf-solid.svg"> [Paper](http://iribis.github.io/files/Perceptual_error_optimization_for_Monte Carlo_animation_rendering/2023-korac-perceptual.pdf)<br />
- <img width="20px" src="http://iribis.github.io/assets/fonts/file-pdf-solid.svg"> [Supplementals Document](http://iribis.github.io/extra/2023_Perceptual_error_optim/2023-korac-perceptual-supp.pdf)<br />
- <i class="fas fa-fw fa-link" aria-hidden="true"></i> [Supplementals](https://misakorac.com/publications/2023_korac_perceptual_error_optimization_for_animation_rendering_data/supplemental_viewer/index.html)<br />
- <i class="fas fa-fw fa-zipper" aria-hidden="true"></i> <a href="http://iribis.github.io/extra/2023_Perceptual_error_optim/2023_korac_tile_data.zip" download="http://iribis.github.io/extra/2023_Perceptual_error_optim/2023_korac_tile_data.zip">Example tiles</a><br />


### BibTeX reference

    @inproceedings{Korac:2023:PerceptualErrorOptimizationAnimation,
        author = {Mi\v{s}a Kora\'{c} and Corentin Sala\"{u}n and Iliyan Georgiev and Pascal Grittmann and Philipp Slusallek and Karol Myszkowski and Gurprit Singh},
        title = {Perceptual error optimization for Monte Carlo animation rendering},
        booktitle = {ACM SIGGRAPH Asia 2023 Conference Proceedings},
        year = {2023},
        doi = {10.1145/3610548.3618146},
        isbn = {979-8-4007-0315-7/23/12}
    }

### Acknowledgements

This project has received funding from the European Union’s Horizon 2020 research and innovation program under Marie SkłodowskaCurie grant agreement no. 956585. We thank the anonymous reviewers for their feedback, and the authors of the following scenes: julioras3d (Chopper), NewSee2l035 (Modern Hall), Benedikt Bitterli (Utah Teapot), Wig42 (Living Room), and Jay Hardy (White Room).