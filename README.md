# Quantifying the impact of the environment on health using Bayesian methods

## Introduction

GitHub repo through which we're developing and sharing materials for the workshop on Quantifying the impact of the environment on health using Bayesian methods, taking place in person during Octover 18th and 21st 2024 at Imperial.

## Notes for attendees

The workshop will be a series of lectures and interactive supervised lab sessions. We hope it's informative and fun!

This workshop is largely written in [`NIMBLE`](https://r-nimble.org/).

Below is the set of labs to follow throughout the two days:

### Day 1 (October 18th 2024)

| Time         | Activity                 |
| ------------ | ------------------------ |
| 8:30 - 9:00  | Check in and Breakfast   |
| 9:00 - 9:15  | [Welcome and Introduction](/lectures/welcome_and_introduction/welcome_and_introduction.qmd) |
| 9:15 - 10:00 | [Introduction to Bayesian Methods](/lectures/introduction_to_bayesian_methods/introduction_to_bayesian_methods.qmd) (Lecture) |
| 10:00  - 10:15 | Break / One-on-one questions
| 10:15  - 11:00 | [Introduction to Bayesian Methods](/labs/introduction_to_bayesian_methods/introduction_to_bayesian_methods.qmd) (Hands-on Lab) |
| 11:00 - 11:15 | Break / One-on-one questions |
| 11:15 - 12:00 | [Bayesian Workflow](/lectures/bayesian_workflow/bayesian_workflow.qmd) (Lecture) |
| 12:00 - 1:00 | Networking Lunch |
| 1:00  - 1:45 | [Bayesian Regression and Temporal Modeling](/lectures/bayesian_regression_and_temporal_modelling/bayesian_regression_and_temporal_modelling.qmd) (Lecture) |
| 1:45  - 2:00 | Break / One-on-one questions |
| 2:00  - 2:45 | [Bayesian Regression and Temporal Modelling](/labs/bayesian_regression_and_temporal_modelling/bayesian_regression_and_temporal_modelling.qmd) (Hands-on Lab) |
| 2:45  - 3:00 | Break / One-on-one questions |
| 3:00  - 3:45 | [Hierarchical Modeling](/lectures/hierarchical_modelling/hierarchical_modelling.qmd) (Lecture) |
| 3:45  - 4:00 | Break / One-on-one questions |
| 4:00  - 4:45 | [Hierarchical Modelling](/labs/hierarchical_modelling/hierarchical_modelling.qmd) (Hands-on Lab) |
| 4:45  - 5:00 | Questions and Wrap-up |

### Day 2 (October 21st 2024)

| Time         | Activity                 |
| ------------ | ------------------------ |
| 8:30 - 9:00 | Check in and Breakfast |
| 9:00 - 10:00 | [Spatial and Spatio-temporal Modeling](/lectures/spatiotemporal_models/sstmodels.qmd) (Lecture) |
| 10:00 - 10:15 | Break / One-on-one questions |
| 10:15 - 11:00 | [Spatial and Spatio-temporal Modelling](/labs/spatiotemporal_models/spatiotemporal_models.qmd) (Hands-on Lab) |
| 11:00 - 11:15 | Break / One-on-one questions |
| 11:15 - 12:00 | [Exposure-response modelling](lectures/exposure_response/exposure_response.qmd) (Lecture) |
| 12:00 - 1:00 | Networking Lunch |
| 1:00 - 2:00 | [Exposure-response modelling](/labs/exposure_response/exposure_response.qmd) (Hands-on Lab) |
| 2:00 - 2:15 | Break / One-on-one questions |
| 2:15 - 3:00 | [Software Options](lectures/software_options/software_options.qmd) (Lecture) |
| 3:00 - 3:15 | Break / One-on-one questions |
| 3:15 - 4:15 | [Software Options](/labs/software_options/software_options.qmd) (Hands-on Lab) |
| 4:15 - 5:00 | Workshop Summary, Interactive Panel Discussion & Course Wrap-up |
| 5:00 - 5:15 | Questions and Wrap-up |

## Notes for those working on the repo

### Using `Quarto` for presentations

Quarto is pretty cool. I won't bore you, but have a look at the [docs](https://quarto.org/docs/guide/). Here, we're using it for [presentations](https://quarto.org/docs/presentations/revealjs/). It's designed by the folks at `RStudio`, so you `R` folk will be happy. Make a `.qmd` file and run `quarto render *.qmd` to generate the `html`, which you can open in browser. We can get fancy and import our own `css` to have a consistent theme for out presentations.
