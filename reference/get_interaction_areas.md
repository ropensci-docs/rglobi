# Find locations at which interactions were observed

Returns all locations (latitude,longitude) of interactions in data base
or area specified in arguments

## Usage

``` r
get_interaction_areas(bbox = NULL, read_csv = read_csv_online, ...)
```

## Arguments

- bbox:

  Coordinates in EPSG:4326 decimal degrees defining "left, bottom,
  right, top" of bounding box

- read_csv:

  function used to find csv associated to query url, defaulting to
  online query method

- ...:

  list of named options to configure GloBI API

## Value

Returns data frame of coordinates

## See also

Other areas:
[`get_interactions_in_area()`](https://docs.ropensci.org/rglobi/reference/get_interactions_in_area.md)

## Examples

``` r
if (FALSE) { # interactive()
get_interaction_areas ()
get_interaction_areas (bbox=c(-67.87,12.79,-57.08,23.32))
}
```
