# ‘rglobi’

R library to access species interaction data of
<http://globalbioticinteractions.org>

[![R-check](https://github.com/ropensci/rglobi/workflows/R-check/badge.svg)](https://github.com/ropensci/rglobi/actions)
[![rstudio mirror
downloads](https://cranlogs.r-pkg.org/badges/rglobi?color=E664A4)](https://github.com/r-hub/cranlogs.app)
[![cran
version](https://www.r-pkg.org/badges/version/rglobi)](https://CRAN.R-project.org/package=rglobi)

## install

To install `rglobi` from
[CRAN](https://CRAN.R-project.org/package=rglobi):

``` r

install.packages("rglobi")
```

Or install development version:

``` r

install.packages("devtools")
devtools::install_github("ropensci/rglobi")
```

## examples

``` r

library(rglobi)
# find all unique prey names of Homo sapiens
prey_of("Homo sapiens")$target_taxon_name
# is a shortcut of
get_interactions_by_taxa(sourcetaxon='Homo sapiens', interactiontype='preysOn')$target_taxon_name

# list of supported interactions types
get_interaction_types()

# all known prey names and locations (latitude, longitude) where birds (Aves) preyed on rodents (Rodentia) in California
obs <- get_interactions_by_taxa(sourcetaxon = "Aves", bbox=c(-125.53344800000002,32.750323,-114.74487299999998,41.574361), targettaxon = "Rodentia", returnobservations=TRUE)
locations <- cbind(obs$target_taxon_name, obs$latitude, obs$longitude)
```

Please see R help pages
(e.g. [`?get_interactions_by_taxa`](https://docs.ropensci.org/rglobi/reference/get_interactions_by_taxa.md)
and [vignettes](https://CRAN.R-project.org/package=rglobi) for more
information.

## tests

Tests can be executed using devtools package.

``` r

# workdir should be rglobi repo root directory (check with getwd())
# install dependencies 
devtools::install('.')
devtools::test()
```

This should reload the library, executes the test_that testcases and
show test reports.

## documentation

roxygen2 is used to generate .Rd and NAMESPACE by running:

``` r

 library(roxygen2)
 roxygenize(".")
```

Vignettes are generated using `knitr` and `markdown` packages.

## meta

Please [report any issues or
bugs](https://github.com/ropensci/rglobi/issues).

This package is part of the [rOpenSci](https://ropensci.org/packages/)
project.
