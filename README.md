
<!-- README.md is generated from README.Rmd. Please edit that file -->

# pets

<!-- badges: start -->
<!-- badges: end -->

The goal of pets is to …

## Installation

You can install the development version of pets like so:

``` r
if(!require("devtools")) {
  install.packages("devtools")
}
devtools::install_github("FISH549/pets")
```

## Example

Here are two simple examples that allow you to express your feelings
about cats.

``` r
library(pets)

## if you like cats
cats(TRUE)
#> [1] "I love cats!"

## if you don't like cats
cats(FALSE)
#> [1] "I am not a cat person."
```
