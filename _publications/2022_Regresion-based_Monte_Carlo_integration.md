---
title: "Regression-based Monte Carlo Integration"
collection: publications
permalink: /publication/2022_Regresion-based_Monte_Carlo_integration
excerpt: ''
date: 2022-07-22
venue: 'ACM Transactions on Graphics, Volume 41'
paperurl: 'https://profs.etsmtl.ca/agruson/publication/2022_RegressionMC/'
citation: 'Salaun, Corentin. (2022). "Regression-based Monte Carlo Integration" <i>ACM Transactions on Graphics, Volume 41</i>.'

header:
  teaser: "http://iribis.github.io/files/regression-based_Monte_Carlo_integration/teaser.jpg"
  thumbnail: "http://iribis.github.io/files/regression-based_Monte_Carlo_integration/thumbnail.jpg"
---

![Teaser](http://iribis.github.io/files/regression-based_Monte_Carlo_integration/teaser.jpg)

### Abstract

 Monte Carlo integration is typically interpreted as an estimator of the expected value using stochastic samples. There exists an alternative interpretation in calculus where Monte Carlo integration can be seen as estimating a constant function -- from the stochastic evaluations of the integrand -- that integrates to the original integral. The integral mean value theorem states that this constant function should be the mean (or expectation) of the integrand. Since both interpretations result in the same estimator, little attention has been devoted to the calculus-oriented interpretation. We show that the calculus-oriented interpretation actually implies the possibility of using a more complex function than a constant one to construct a more efficient estimator for Monte Carlo integration. We build a new estimator based on this interpretation and relate our estimator to control variates with least-squares regression on the stochastic samples of the integrand. Unlike prior work, our resulting estimator is provably better than or equal to the conventional Monte Carlo estimator. To demonstrate the strength of our approach, we introduce a practical estimator that can act as a simple drop-in replacement for conventional Monte Carlo integration. We experimentally validate our framework on various light transport integrals. 

### Downloads and links
- <img width="20px" src="http://iribis.github.io/assets/fonts/file-pdf-solid.svg"> [Paper](http://iribis.github.io/files/regression-based_Monte_Carlo_integration/regression-based_Monte_Carlo_integration.pdf)<br />
- <i class="fas fa-fw fa-link" aria-hidden="true"></i> [Supplementals](http://adrien-gruson.com/research/2022_RegressionMC/)<br />
- <i class="fab fa-fw fa-github" aria-hidden="true"></i> [Code](https://github.com/iribis/regressionmc)

### Presentation video

<iframe
    width="640"
    height="380"
    src="https://www.youtube.com/embed/CWVn3L_JghM"
    frameborder="0"
    allow="autoplay; encrypted-media"
    allowfullscreen
>
</iframe>

### BibTeX reference

    @article{Salaun:2022:RegressionMC,
        author = {Sala"{u}n, Corentin and Gruson, Adrien and Hua, Binh-Son and Hachisuka, Toshiya and Singh, Gurprit},
        title = {Regression-Based Monte Carlo Integration},
        year = {2022},
        volume = {41},
        number = {4},
        doi = {10.1145/3528223.3530095},
        journal = {ACM Trans. Graph.},
    }   