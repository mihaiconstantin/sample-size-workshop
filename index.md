<!-- Repository title. -->
<h1 align="center">
    Workshop on Sample Size Planning for
    <br>
    Intensive Longitudinal Studies
</h1>

<!-- Authors. -->
<p align="center">
    <a href="presenters/ginette-lafit.md">Ginette Lafit</a>,
    <a href="presenters/jordan-revol.md">Jordan Revol</a>,
    <a href="presenters/mihai-constantin.md">Mihai A. Constantin</a>, &
    <a href="presenters/eva-ceulemans.md">Eva Ceulemans</a>
</p>

## 📝 Description

In recent years the popularity of procedures to collect intensive longitudinal
data such as the Experience Sampling Method has increased immensely. The data
collected using such designs allow researchers to study the dynamics of
psychological processes, and how these dynamics differ across individuals. A
fundamental question when designing a study is how to determine the sample size,
which is closely related to the replicability and generalizability of empirical
findings. Even though multiple statistical guidelines are available for sample
size planning, it still remains a demanding enterprise in complex designs. The
goal of this workshop is to address this crucial question by presenting
methodological advances for sample size planning for intensive longitudinal
designs. First, we provide an overview of methods for sample size planning with
special emphasis on a priori power analysis. Second, we focus on how to conduct
power analysis in the $N = 1$ case when the goal is to model within-person
processes using $\text{VAR}(1)$ models. Subsequently, we consider the extension
to multilevel data in which multiple individuals are measured over time. We
introduce an approach for conducting power analysis for multilevel models that
explicitly accounts for the temporal dependencies that characterize the data
collected in intensive longitudinal studies. In addition, we showcase how to
perform power analysis for these models using a user-friendly and open-source
application. Finally, we consider an alternative criterion for conducting sample
size planning that targets the predictive accuracy of a model for unseen data.
Focusing on $\text{VAR}(1)$ models in an $N = 1$ context, we introduce a novel
approach, called predictive accuracy analysis, to assess how many measurement
occasions are required in order to optimize predictive accuracy.

## 📊 Learning Objectives

The workshop provides a *road map* on how to determine the sample size in
intensive longitudinal designs. Upon course completion, participants will:

- be familiar with methods for conducting power analysis for $\text{AR}(1)$ and
  $\text{VAR}(1)$ models in $N = 1$ and multilevel intensive longitudinal
  designs
- understand the key differences between simulation-based and analytical power
  analysis approaches
- be able to leverage existing tools for conducting power analysis for
  $\text{AR}(1)$ and $\text{VAR}(1)$ for intensive longitudinal designs
- be familiar with new methods for conducting sample size analysis based on
  criteria different than statistical power (e.g., predictive accuracy or
  sensitivity)

## 💻 Prerequisites

Participants should have some basic knowledge of `R` and some experience with
`RStudio`. For the hands-on parts of the workshop, you need to install `R`
version `4.1.2` or higher, `RStudio`, and several `R` packages as indicated on
the page corresponding to each exercise.

Some exercises in this workshop also involve using `Shiny` applications to run
power analysis. You can find additional instructions on how to download and run
the `Shiny` applications below:

- for [Predictive Accuracy Analysis and power analysis for the $\text{VAR}(1)$][1]
- for [power analysis for multilevel models using the simulation-based approach][2]
- for [power analysis for multilevel models using the analytic approach][3]

You can find detailed instructions and examples for conducting sample size
analysis using the `powerly` package at [powerly.dev](https://powerly.dev/).

## 📂 Modules

| Topic                                                                                | Duration |                              Slides                              |                                                                                             Tutorial                                                                                              |
| :----------------------------------------------------------------------------------- | :------: | :--------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Introduction to sample size planning in intensive longitudinal research              |   45m    | [[slides]{.badge .rounded-pill .bg-primary}][slides-intensive-1] |                                                                                                 -                                                                                                 |
| Sample size planning for $\text{VAR}(1)$ models in $N = 1$ designs                   |   60m    | [[slides]{.badge .rounded-pill .bg-primary}][slides-intensive-2] |                                 [[tutorial 1]{.badge .rounded-pill .bg-primary}][ex-n-1-power] [[tutorial 2]{.badge .rounded-pill .bg-primary}][ex-n-1-solutions]                                 |
| Sample size planning for multilevel models applied to intensive longitudinal designs |   50m    | [[slides]{.badge .rounded-pill .bg-primary}][slides-intensive-3] | [[tutorial 1]{.badge .rounded-pill .bg-primary}][ex-ml-estimation] [[tutorial 2]{.badge .rounded-pill .bg-primary}][ex-ml-interaction] [[tutorial 3]{.badge .rounded-pill .bg-primary}][ex-ml-ar] |
| Advanced methods for sample size analysis                                            |   40m    |  [[slides]{.badge .rounded-pill .bg-primary}][slides-advanced]   |                                                                    [[tutorial]{.badge .rounded-pill .bg-primary}][ex-powerly]                                                                     |

## 📍 Given At

| Conference | Location                   | Date           |                                                 Link                                                  |
| :--------- | :------------------------- | :------------- | :---------------------------------------------------------------------------------------------------: |
| SAA 2023   | Amsterdam, The Netherlands | June 8th, 2023 | [<span class="badge rounded-pill bg-success">link</span>](https://www.saa2023.nl/amsterdam/workshops) |

## ✍️ Citation

- Lafit, G., Revol, J., Constantin M. A., & Ceulemans, E. (2023). *Workshop on
  Sample Size Planning for Intensive Longitudinal Studies*.
  https://00.0000/zenodo.0000000

## ⚖️ License

- <p class="license-cc" xmlns:cc="https://creativecommons.org/ns#" xmlns:dct="https://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/mihaiconstantin/sample-size-workshop">The scripts, slides, and other materials</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://github.com/mihaiconstantin/sample-size-workshop#citation">Ginette Lafit, Jordan Revol, Mihai A. Constantin, and Eva Ceulemans</a> are licensed under <a href="https://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY 4.0 <img style="height:22px!important" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"> <img style="height:22px!important" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"></a>.</p>

<!-- Reference links. -->
[1]: https://gitlab.kuleuven.be/ppw-okpiv/researchers/u0148925/shinyapp-paa_var_n1
[2]: https://github.com/ginettelafit/PowerAnalysisIL
[3]: https://gitlab.kuleuven.be/ppw-okpiv/researchers/u0119584/ApproxPowerIL

<!-- Slide links. -->
[slides-intensive-1]: slides/intensive-longitudinal.pdf
[slides-intensive-2]: slides/intensive-longitudinal.pdf#page=23
[slides-intensive-3]: slides/intensive-longitudinal.pdf#page=61
[slides-advanced]: slides/advanced-methods.pdf

<!-- Exercise links Jordan. -->
[ex-n-1-power]: exercises/power-simulation-n-1-intensive-designs.Rmd
[ex-n-1-solutions]: exercises/sample-size-solutions-n-1-intensive-designs.Rmd

<!-- Exercise links Ginette. -->
[ex-ml-estimation]: exercises/estimation-multilevel-leuven-clinical-data.Rmd
[ex-ml-interaction]: exercises/power-multilevel-cross-level-interaction-intensive-designs.Rmd
[ex-ml-ar]: exercises/power-multilevel-ar-intensive-designs.Rmd

<!-- Myself. -->
[ex-powerly]: exercises/sample-size-analysis-powerly.qmd
