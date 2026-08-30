# List data fields identified in GloBI database

Returns data frame with supported data fields

## Usage

``` r
get_data_fields(opts = list(), read_csv = read_csv_online)
```

## Arguments

- opts:

  list of named options to configure GloBI API

- read_csv:

  function used to find csv associated to query url, defaulting to
  online query method

## Value

Returns data frame of supported data fields

## Examples

``` r
# \donttest{
get_data_fields()
#> Error: cannot open the connection
# }
```
