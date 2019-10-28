
<!-- README.md is generated from README.Rmd. Please edit that file -->

# opinion.classifier

<!-- badges: start -->

[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
[![CRAN
status](https://www.r-pkg.org/badges/version/opinion.classifier)](https://CRAN.R-project.org/package=opinion.classifier)
[![Travis build
status](https://travis-ci.org/mkearney/opinion.classifier.svg?branch=master)](https://travis-ci.org/mkearney/opinion.classifier)
[![AppVeyor build
status](https://ci.appveyor.com/api/projects/status/github/mkearney/opinion.classifier?branch=master&svg=true)](https://ci.appveyor.com/project/mkearney/opinion.classifier)
<!-- badges: end -->

A machine learning classification model for measuring opinion, or
editorial, content in news text. The model was trained using editorial
and news content from highly regarded, well-known journalism outlets.

## Installation

You can install the released version of opinion.classifier from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("opinion.classifier")
```

or the development version from Github

``` r
remotes::install_github("mkearney/opinion.classifier")
```

## Example

Get opinion probability estimate

``` r
opinion.classifier::opinion_score(x)
```
