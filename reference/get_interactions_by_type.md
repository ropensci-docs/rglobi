# Get Species Interactions by Interaction Type from GloBI

Get Species Interactions by Interaction Type from GloBI

## Usage

``` r
get_interactions_by_type(interactiontype = c("interactsWith"), ...)
```

## Arguments

- interactiontype:

  the requested interaction type (e.g. preysOn)

- ...:

  list of options to configure GloBI API

## Value

species interactions given provided interaction type(s)

## See also

Other interactions:
[`get_interaction_matrix()`](https://docs.ropensci.org/rglobi/reference/get_interaction_matrix.md),
[`get_interaction_types()`](https://docs.ropensci.org/rglobi/reference/get_interaction_types.md),
[`get_interactions_by_taxa()`](https://docs.ropensci.org/rglobi/reference/get_interactions_by_taxa.md),
[`get_interactions()`](https://docs.ropensci.org/rglobi/reference/get_interactions.md),
[`get_predators_of()`](https://docs.ropensci.org/rglobi/reference/get_predators_of.md),
[`get_prey_of()`](https://docs.ropensci.org/rglobi/reference/get_prey_of.md)

## Examples

``` r
# \donttest{
get_interactions_by_type(interactiontype = c("eats", "eatenBy"))
#> Error: cannot open the connection
get_interactions_by_type(interactiontype = "parasiteOf")
#> Error: cannot open the connection
# }
```
