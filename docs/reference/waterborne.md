# data from CDC on waterborne and foodborne illness events

data from CDC on waterborne and foodborne illness events

## Usage

``` r
data(waterborne)
```

## Format

An object of class `list` of length 66713.

## Note

The source is `https://data.cdc.gov/api/v3/views/5xkq-dg7x/query.json`
Run the example to see metadata labels.

## Examples

``` r
data("waterborne", package="bst260project")
#> Error in find.package(package, lib.loc, verbose = verbose): there is no package called ‘bst260project’
unique(unlist(lapply(waterborne, names)))
#> Error: object 'waterborne' not found
waterborne[[1]]
#> Error: object 'waterborne' not found
```
