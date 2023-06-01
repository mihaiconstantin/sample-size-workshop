<!-- Repository title. -->
<h1 align="center">
    Workshop on Sample Size Planning for
    <br>
    Intensive Longitudinal Studies
</h1>

<!-- Authors. -->
<p align="center">
    <a href="https://ppw.kuleuven.be/okp/team/Ginette_Lafit/">Ginette Lafit</a>,
    <a href="https://ppw.kuleuven.be/okp/team/Jordan_Revol/">Jordan Revol</a>,
    <a href="https://mihaiconstantin.com/">Mihai A. Constantin</a>, &
    <a href="https://ppw.kuleuven.be/okp/team/Eva_Ceulemans/">Eva Ceulemans</a>
</p>

## Description

In recent years the popularity of procedures to collect intensive longitudinal
(IL) data such as the Experience Sampling Method has increased immensely. The
data collected using such designs allow researchers to study the dynamics of
psychological processes, and how these dynamics differ across individuals. A
fundamental question when designing a study is how to determine the sample size,
which is closely related to the replicability and generalizability of empirical
findings. Even though multiple statistical guidelines are available for sample
size planning, it still remains a demanding enterprise in complex designs. The
goal of this workshop is to address this crucial question by presenting
methodological advances for sample size planning for IL designs. First, we
provide an overview of methods for sample size planning with special emphasis on
a priori power analysis. Second, we focus on how to conduct power analysis in
the $N = 1$ case when the goal is to model within-person processes using
$VAR(1)$ models. Subsequently, we consider the extension to multilevel data in
which multiple individuals are measured over time. We introduce an approach for
conducting power analysis for multilevel models that explicitly accounts for the
temporal dependencies that characterize the data collected in IL studies. In
addition, we showcase how to perform power analysis for these models using a
user-friendly and open-source application. Finally, we consider an alternative
criterion for conducting sample size planning that targets the predictive
accuracy of a model for unseen data. Focusing on $VAR(1)$ models in an $N = 1$
context, we introduce a novel approach, called predictive accuracy analysis, to
assess how many measurement occasions are required in order to optimize
predictive accuracy.

## Learning Objectives

The workshop provides a *road map* on how to determine the sample size in IL
designs.

Upon course completion, participants will:

- be familiar with methods for conducting power analysis for $AR(1)$ and
  $VAR(1)$ models in $N = 1$ IL designs
- understand the different steps of the simulation-based power analysis approach
- be able to implement existing tool for conducting power analysis for $AR(1)$
  and $VAR(1)$ models in $N = 1$ IL designs
- be familiar with an new methods for conducting sample size analysis based on
  criteria different than statistical power (e.g., predictive accuracy or
  sensitivity)

## Prerequisites

Participants should have some basic knowledge of `R` and some experience with
`RStudio`. For the hands-on parts of the workshop, you need to install `R`
version `4.1.2` or higher, `RStudio`, and the following `R` packages:

- [`data.table`](https://CRAN.R-project.org/package=data.table)
- [`psych`](https://CRAN.R-project.org/package=psych)
- [`ggplot2`](https://CRAN.R-project.org/package=ggplot2)
- [`tidyverse`](https://www.tidyverse.org/packages/)
- [`powerly`](https://CRAN.R-project.org/package=powerly)

## Modules

| Topic                        | Duration |      Slides      |     Tutorial     |
| :--------------------------- | :------: | :--------------: | :--------------: |
| Sample Size Planning         |   0.0h   | [link](https://) | [link](https://) |
| $N = 1$: Introduction        |   0.0h   | [link](https://) | [link](https://) |
| $N = 1$: Predictive Accuracy |   0.0h   | [link](https://) | [link](https://) |
| Multilevel models            |   0.0h   | [link](https://) | [link](https://) |
| Advanced methods             |   0.0h   | [link](https://) | [link](https://) |
| Take home                    |   0.0h   | [link](https://) | [link](https://) |

## Given At

| Conference | Location                   | Date           |                        Link                        |
| :--------- | :------------------------- | :------------- | :------------------------------------------------: |
| SAA 2023   | Amsterdam, The Netherlands | June 8th, 2023 | [link](https://www.saa2023.nl/amsterdam/workshops) |

## Presenters

- [Ginette Lafit]
  - PostDoc at Research Group of Quantitative Psychology and Individual Differences and Center of Contextual Psychiatry, KU Leuven
  - Research interests:
    - Statistical methods for IL designs
    - Methodology & open science in ESM research

- [Jordan Revol]
  - PhD candidate at Research Group of Quantitative Psychology and Individual Differences, KU Leuven
  - Research interests:
    - Statistical methods for IL designs
    - Sample size planning methods & Predictive accuracy in IL studies

- [Mihai A. Constantin]
  - PhD candidate at Department of Methodology and Statistics, Tilburg University
  - Research interests:
    - Computational statistics and software [tools](https://github.com/mihaiconstantin) for social sciences
    - Simulation-based methods for sample size analysis

- [Eva Ceulemans]
  - Professor of Quantitative Psychology and Individual Differences, KU Leuven
  - Research interests:
    - Dimension reduction methods for multiset and multiway data
    - Statistical methods for IL designs

## Citation

- Lafit, G., Revol, J., Constantin M. A., & Ceulemans, E. (2023). *Workshop on
  Sample Size Planning for Intensive Longitudinal Studies*.
  https://00.0000/zenodo.0000000

## License

- <p class="license-cc" xmlns:cc="https://creativecommons.org/ns#" xmlns:dct="https://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/mihaiconstantin/sample-size-workshop">The scripts, slides, and other materials</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://github.com/mihaiconstantin/sample-size-workshop#citation">Ginette Lafit, Jordan Revol, Mihai A. Constantin, and Eva Ceulemans</a> are licensed under <a href="https://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY 4.0 <img style="height:22px!important" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"> <img style="height:22px!important" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"></a>.</p>

<!-- Links. -->
[Ginette Lafit]: https://ppw.kuleuven.be/okp/team/Ginette_Lafit/
[Jordan Revol]: https://ppw.kuleuven.be/okp/team/Jordan_Revol/
[Mihai A. Constantin]: https://mihaiconstantin.com/
[Eva Ceulemans]: https://ppw.kuleuven.be/okp/team/Eva_Ceulemans/
