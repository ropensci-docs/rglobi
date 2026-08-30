# Get Interaction Matrix. Constructs an interaction matrix indicating whether source taxa (rows) or target taxa (columns) are known to interact with given type.

Get Interaction Matrix. Constructs an interaction matrix indicating
whether source taxa (rows) or target taxa (columns) are known to
interact with given type.

## Usage

``` r
get_interaction_matrix(
  source.taxon.names = list("Homo sapiens"),
  target.taxon.names = list("Mammalia"),
  interaction.type = "eats",
  opts = list(),
  read_csv = read_csv_online
)
```

## Arguments

- source.taxon.names:

  list of source taxon names (e.g. list('Mammalia', 'Aves', 'Ariopsis
  felis'))

- target.taxon.names:

  list of target taxon names

- interaction.type:

  the preferred interaction type (e.g. preysOn)

- opts:

  list of options to configure GloBI API

- read_csv:

  function used to find csv associated to query url, defaulting to
  online query method

## Value

matrix representing species interactions between source and target taxa

## See also

Other interactions:
[`get_interaction_types()`](https://docs.ropensci.org/rglobi/reference/get_interaction_types.md),
[`get_interactions_by_taxa()`](https://docs.ropensci.org/rglobi/reference/get_interactions_by_taxa.md),
[`get_interactions_by_type()`](https://docs.ropensci.org/rglobi/reference/get_interactions_by_type.md),
[`get_interactions()`](https://docs.ropensci.org/rglobi/reference/get_interactions.md),
[`get_predators_of()`](https://docs.ropensci.org/rglobi/reference/get_predators_of.md),
[`get_prey_of()`](https://docs.ropensci.org/rglobi/reference/get_prey_of.md)

## Examples

``` r
# \donttest{
get_interaction_matrix("Homo sapiens", "Mammalia", "interactsWith")
#> Error: cannot open the connection
# }
```
