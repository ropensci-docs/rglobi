# Get a List of Predators of a Given Prey Taxon

Get a List of Predators of a Given Prey Taxon

## Usage

``` r
get_predators_of(taxon = "Rattus rattus", ...)
```

## Arguments

- taxon:

  scientific name of prey taxon. Can be any taxonomic rank (e.g. Rattus
  rattus, Decapoda)

- ...:

  list of named options to configure the GloBI API

## Value

list of recorded prey-predator interactions that involve the desired
prey taxon.

## See also

Other interactions:
[`get_interaction_matrix()`](https://docs.ropensci.org/rglobi/reference/get_interaction_matrix.md),
[`get_interaction_types()`](https://docs.ropensci.org/rglobi/reference/get_interaction_types.md),
[`get_interactions_by_taxa()`](https://docs.ropensci.org/rglobi/reference/get_interactions_by_taxa.md),
[`get_interactions_by_type()`](https://docs.ropensci.org/rglobi/reference/get_interactions_by_type.md),
[`get_interactions()`](https://docs.ropensci.org/rglobi/reference/get_interactions.md),
[`get_prey_of()`](https://docs.ropensci.org/rglobi/reference/get_prey_of.md)

## Examples

``` r
# \donttest{
get_predators_of("Rattus rattus")
#> Error: cannot open the connection
get_predators_of("Primates")
#> Error: cannot open the connection
# }
```
