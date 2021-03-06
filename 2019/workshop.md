# SatRday LA 2019 Workshop

Workshop | Instructor| More info
---------|--------------|--------
Building an R Package in 45 Minutes | David Edison | [>](#Building-an-R-Package-in-45-Minutes)
Predictive Analytics in R and Prediction Error | Alfonso Berumen | [>](#Predictive-Analytics-in-R-and-Prediction-Error)
Text Classification in tidymodels | Emil Hvitfeldt | [>](#Text-Classification-in-tidymodels)

---

## Building an R Package in 45 Minutes
#### David Edison
##### Data Scientist - Nordstrom
This session will be a live-coding session using the `usethis` and `devtools` packages to build a fully functional R package from scratch. The content of the package will be a simple toy function, some sample data, and some tests using `testthat`. Additionally, this workshop will cover some background about the various directories / files necessary for an R package, as well as some other tips and tricks that RStudio provides to make building an R package as easy as possible.

In order to ensure the workshop goes as smoothly as possible, it is recommended to install the R packages `usethis`, `devtools`, `crayon`, and `clisymbols` (all of which are available on CRAN) prior to the start of the session.

Recommended Reading:

* [usethis Documentation by Hadley Wickham / Jenny Bryan](https://usethis.r-lib.org/)
* [R Packages by Hadley Wickham]( http://r-pkgs.had.co.nz/) 
* [Writing R Extensions by the R Core Team](https://cran.r-project.org/doc/manuals/r-release/R-exts.html)

## Predictive Analytics in R and Prediction Error
#### Alfonso Berumen
##### UCLAx Data Science Instructor & Independent Consultant
[Slides](https://github.com/satRdays/losangeles/blob/master/2019/slides/11Workshops/10-02Facebook_metrics.pdf)

This session will cover the basics of conducting Predictive Analytics in R. The presenter will cover the basis of training/test partitions, evaluation of models, and measurement of prediction error. The presenter will use a case study approach to demonstrate why measurement of error is important when conducting Predictive Analytics. The presenter will ask students/attendees to consider not just error in the classical sense of the difference between predicted and actual values but also error in the context of the problem (i.e., dollars, number of people, or other units/quantities related to what is being modeled).

## Text Classification in tidymodels
#### Emil Hvitfeldt 
##### Research Programmer at USC, co-organizer of @laeRusers and free time R developer

With an ever-increasing amount of textual data is available us, having a well-thought-out toolchain for modeling is crucial. tidymodels is a recent effort to create a modeling framework that share the underlying design philosophy, grammar, and data structures of the tidyverse. textrecipes joined the roster late last year and provided a exciting bridge to text preprocessing. This talk will go though the process and complications of implementing textrecipes along with example workflows.
