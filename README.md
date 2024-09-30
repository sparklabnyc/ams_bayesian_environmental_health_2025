# Introduction to Bayesian Methods for Environmental Health and Beyond

## Introduction

GitHub repo through which we're developing and sharing materials for the workshop on [Introduction to Bayesian Methods for Environmental Health and Beyond](https://www.ametsoc.org/index.cfm/ams/education-careers/careers/professional-development/short-courses/introduction-to-bayesian-methods-for-environmental-health-and-beyond/), taking place in person during January 12th 2025, 8:00 AM - 3:30 PM, at the American Meteorological Society conference in New Orleans, United States.

We would like to acknowledge [Theo O. Rashid](https://www.imperial.ac.uk/people/theo.rashid15) and [Elizaveta Semenova](https://www.cs.ox.ac.uk/people/elizaveta.semenova/) for their contribution to the lecture material and R code. 

## Notes for attendees

The workshop will be a series of lectures and interactive supervised lab sessions. We hope it's informative and fun!

This workshop is largely written in [`NIMBLE`](https://r-nimble.org/).

Below is the set of labs to follow throughout the day:

### January 12th 2025

| Time         | Activity                 |
| ------------ | ------------------------ |
| 7:45 - 8:00  | Check in and Breakfast   |
| 8:00 - 8:15  | [Welcome and Introduction](/lectures/welcome_and_introduction/welcome_and_introduction.qmd) |
| 08:15 - 09:00 | [Introduction to Bayesian Methods](/lectures/introduction_to_bayesian_methods/introduction_to_bayesian_methods.qmd) (Lecture) |
| 09:00 - 09:45 | [Introduction to Bayesian Methods](/labs/introduction_to_bayesian_methods/introduction_to_bayesian_methods.qmd) (Hands-on Lab) |
| 09:45 - 10:00 | Break |
| 10:00 - 10:45 | [Hierarchical Modeling](/lectures/hierarchical_modelling/hierarchical_modelling.qmd) (Lecture) |
| 10:45 - 11:30 | [Hierarchical Modelling](/labs/hierarchical_modelling/hierarchical_modelling.qmd) (Hands-on Lab) |
| 11:30  - 12:15 | Networking lunch |
| 12:15 - 13:00 | [Spatial and Spatio-temporal Modeling](/lectures/spatiotemporal_models/sstmodels.qmd) (Lecture) |
| 13:00 - 13:45 | [Spatial and Spatio-temporal Modelling](/labs/spatiotemporal_models/spatiotemporal_models.qmd) (Hands-on Lab) |
| 13:45 - 14:00 | Break |
| 14:00 - 14:45 | [Exposure-response modelling](lectures/exposure_response/exposure_response.qmd) (Lecture) |
| 14:45 - 15:30 | [Exposure-response modelling](/labs/exposure_response/exposure_response.qmd) (Hands-on Lab) |

## Notes for those working on the repo

### Using `pre-commit`

Run `pre-commit install` to install the hooks. You now won't be able to commit until you pass the hooks. These (among other things) automatically format files and prevent us from committing ugly code. For more details, see the main [docs](https://pre-commit.com/) and the `R` [docs](https://lorenzwalthert.github.io/precommit/).

### Using `renv`

`renv` maintains consistency between users' `R` environments. Run `renv::restore()` and the environment will be downloaded into the repository based on the `renv.lock` file. If you want to add a packages to the lockfile, install the package and then run `renv::snapshot()`. For more details, see the [docs](https://rstudio.github.io/renv/articles/renv.html).

### Using `Quarto` for presentations

Quarto is pretty cool. I won't bore you, but have a look at the [docs](https://quarto.org/docs/guide/). Here, we're using it for [presentations](https://quarto.org/docs/presentations/revealjs/). It's designed by the folks at `RStudio`, so you `R` folk will be happy. Make a `.qmd` file and run `quarto render *.qmd` to generate the `html`, which you can open in browser. We can get fancy and import our own `css` to have a consistent theme for out presentations.
