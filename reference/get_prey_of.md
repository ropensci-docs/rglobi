# Get a List of Prey for given Predator Taxon

Get a List of Prey for given Predator Taxon

## Usage

``` r
get_prey_of(taxon = "Homo sapiens", ...)
```

## Arguments

- taxon:

  scientific name of predator taxon. Can be any taxonomic rank (e.g.
  Homo sapiens, Animalia)

- ...:

  list of named options to configure GloBI API

## Value

list of recorded predator-prey interactions that involve the desired
predator taxon

## See also

Other interactions:
[`get_interaction_matrix()`](https://docs.ropensci.org/rglobi/reference/get_interaction_matrix.md),
[`get_interaction_types()`](https://docs.ropensci.org/rglobi/reference/get_interaction_types.md),
[`get_interactions_by_taxa()`](https://docs.ropensci.org/rglobi/reference/get_interactions_by_taxa.md),
[`get_interactions_by_type()`](https://docs.ropensci.org/rglobi/reference/get_interactions_by_type.md),
[`get_interactions()`](https://docs.ropensci.org/rglobi/reference/get_interactions.md),
[`get_predators_of()`](https://docs.ropensci.org/rglobi/reference/get_predators_of.md)

## Examples

``` r
# \donttest{
get_prey_of("Homo sapiens")
#> Error: cannot open the connection
get_prey_of("Primates")
#> Error: cannot open the connection
# }
```
