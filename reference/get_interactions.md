# Get Species Interaction from GloBI

Get Species Interaction from GloBI

## Usage

``` r
get_interactions(taxon = "Homo sapiens", interaction.type = "preysOn", ...)
```

## Arguments

- taxon:

  canonical scientific name of source taxon (e.g. Homo sapiens)

- interaction.type:

  the preferred interaction type (e.g. preysOn)

- ...:

  list of options to configure GloBI API

## Value

species interactions between source and target taxa

## See also

Other interactions:
[`get_interaction_matrix()`](https://docs.ropensci.org/rglobi/reference/get_interaction_matrix.md),
[`get_interaction_types()`](https://docs.ropensci.org/rglobi/reference/get_interaction_types.md),
[`get_interactions_by_taxa()`](https://docs.ropensci.org/rglobi/reference/get_interactions_by_taxa.md),
[`get_interactions_by_type()`](https://docs.ropensci.org/rglobi/reference/get_interactions_by_type.md),
[`get_predators_of()`](https://docs.ropensci.org/rglobi/reference/get_predators_of.md),
[`get_prey_of()`](https://docs.ropensci.org/rglobi/reference/get_prey_of.md)

## Examples

``` r
# \donttest{
get_interactions("Homo sapiens", "preysOn")
#> Error: cannot open the connection
get_interactions("Insecta", "parasiteOf")
#> Error: cannot open the connection
# }
```
