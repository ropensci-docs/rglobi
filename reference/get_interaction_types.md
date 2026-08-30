# List interactions identified in GloBI database

Returns data frame with supported interaction types

## Usage

``` r
get_interaction_types(opts = list(), read_csv = read_csv_online)
```

## Arguments

- opts:

  list of named options to configure GloBI API

- read_csv:

  function used to find csv associated to query url, defaulting to
  online query method

## Value

Returns data frame of supported interaction types

## See also

Other interactions:
[`get_interaction_matrix()`](https://docs.ropensci.org/rglobi/reference/get_interaction_matrix.md),
[`get_interactions_by_taxa()`](https://docs.ropensci.org/rglobi/reference/get_interactions_by_taxa.md),
[`get_interactions_by_type()`](https://docs.ropensci.org/rglobi/reference/get_interactions_by_type.md),
[`get_interactions()`](https://docs.ropensci.org/rglobi/reference/get_interactions.md),
[`get_predators_of()`](https://docs.ropensci.org/rglobi/reference/get_predators_of.md),
[`get_prey_of()`](https://docs.ropensci.org/rglobi/reference/get_prey_of.md)

## Examples

``` r
# \donttest{
get_interaction_types()
#> Error: cannot open the connection
# }
```
