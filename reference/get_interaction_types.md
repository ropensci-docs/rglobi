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
[`get_interactions()`](https://docs.ropensci.org/rglobi/reference/get_interactions.md),
[`get_interactions_by_taxa()`](https://docs.ropensci.org/rglobi/reference/get_interactions_by_taxa.md),
[`get_interactions_by_type()`](https://docs.ropensci.org/rglobi/reference/get_interactions_by_type.md),
[`get_predators_of()`](https://docs.ropensci.org/rglobi/reference/get_predators_of.md),
[`get_prey_of()`](https://docs.ropensci.org/rglobi/reference/get_prey_of.md)

## Examples

``` r
# \donttest{
get_interaction_types()
#>                     interaction       source       target
#> 1                          eats     consumer         food
#> 2                       eatenBy         food     consumer
#> 3                       preysOn     predator         prey
#> 4                  preyedUponBy         prey     predator
#> 5                         kills       killer       victim
#> 6                      killedBy       victim       killer
#> 7                    parasiteOf     parasite         host
#> 8                   hasParasite         host     parasite
#> 9                endoparasiteOf endoparasite         host
#> 10              hasEndoparasite         host endoparasite
#> 11               ectoparasiteOf ectoparasite         host
#> 12              hasEctoparasite         host ectoparasite
#> 13                 parasitoidOf   parasitoid         host
#> 14                hasParasitoid         host   parasitoid
#> 15                       hostOf         host     symbiont
#> 16                      hasHost     symbiont         host
#> 17                   pollinates   pollinator        plant
#> 18                 pollinatedBy        plant   pollinator
#> 19                   pathogenOf     pathogen         host
#> 20                 allelopathOf     pathogen         host
#> 21                  hasPathogen         host     pathogen
#> 22                     vectorOf       vector     pathogen
#> 23                    hasVector     pathogen       vector
#> 24            dispersalVectorOf       vector         seed
#> 25           hasDispersalVector         seed       vector
#> 26               rootparasiteOf     parasite    plantRoot
#> 27               hemiparasiteOf     parasite        plant
#> 28                   hasHabitat   inhabitant      habitat
#> 29            createsHabitatFor      habitat   inhabitant
#> 30                   epiphyteOf  plant/algae   host plant
#> 31                  hasEpiphyte        plant  plant/algae
#> 32        ectomycorrhizalHostOf   plant root       fungus
#> 33       hasEctomycorrhizalHost       fungus   plant root
#> 34  arbuscularMycorrhizalHostOf   plant root       fungus
#> 35 hasArbuscularMycorrhizalHost       fungus   plant root
#> 36         providesNutrientsFor         host     consumer
#> 37        acquiresNutrientsFrom     consumer         host
#> 38                   symbiontOf     symbiont     symbiont
#> 39                  mutualistOf    mutualist    mutualist
#> 40               commensalistOf commensalist commensalist
#> 41             flowersVisitedBy        plant      visitor
#> 42              visitsFlowersOf      visitor        plant
#> 43                    visitedBy         host      visitor
#> 44                       visits      visitor         host
#> 45        ecologicallyRelatedTo       source       target
#> 46                 coOccursWith       source       target
#> 47                 coRoostsWith       source       target
#> 48                interactsWith       source       target
#> 49                   adjacentTo       source       target
#>                                      termIRI
#> 1  http://purl.obolibrary.org/obo/RO_0002470
#> 2  http://purl.obolibrary.org/obo/RO_0002471
#> 3  http://purl.obolibrary.org/obo/RO_0002439
#> 4  http://purl.obolibrary.org/obo/RO_0002458
#> 5  http://purl.obolibrary.org/obo/RO_0002626
#> 6  http://purl.obolibrary.org/obo/RO_0002627
#> 7  http://purl.obolibrary.org/obo/RO_0002444
#> 8  http://purl.obolibrary.org/obo/RO_0002445
#> 9  http://purl.obolibrary.org/obo/RO_0002634
#> 10 http://purl.obolibrary.org/obo/RO_0002635
#> 11 http://purl.obolibrary.org/obo/RO_0002632
#> 12 http://purl.obolibrary.org/obo/RO_0002633
#> 13 http://purl.obolibrary.org/obo/RO_0002208
#> 14 http://purl.obolibrary.org/obo/RO_0002209
#> 15 http://purl.obolibrary.org/obo/RO_0002453
#> 16 http://purl.obolibrary.org/obo/RO_0002454
#> 17 http://purl.obolibrary.org/obo/RO_0002455
#> 18 http://purl.obolibrary.org/obo/RO_0002456
#> 19 http://purl.obolibrary.org/obo/RO_0002556
#> 20 http://purl.obolibrary.org/obo/RO_0002555
#> 21 http://purl.obolibrary.org/obo/RO_0002557
#> 22 http://purl.obolibrary.org/obo/RO_0002459
#> 23 http://purl.obolibrary.org/obo/RO_0002460
#> 24                                  no:match
#> 25                                  no:match
#> 26 http://purl.obolibrary.org/obo/RO_0002236
#> 27 http://purl.obolibrary.org/obo/RO_0002237
#> 28 http://purl.obolibrary.org/obo/RO_0002303
#> 29 http://purl.obolibrary.org/obo/RO_0008505
#> 30 http://purl.obolibrary.org/obo/RO_0008501
#> 31 http://purl.obolibrary.org/obo/RO_0008502
#> 32 http://purl.obolibrary.org/obo/RO_0002804
#> 33 http://purl.obolibrary.org/obo/RO_0002805
#> 34 http://purl.obolibrary.org/obo/RO_0002806
#> 35 http://purl.obolibrary.org/obo/RO_0002807
#> 36 http://purl.obolibrary.org/obo/RO_0002469
#> 37 http://purl.obolibrary.org/obo/RO_0002457
#> 38 http://purl.obolibrary.org/obo/RO_0002440
#> 39 http://purl.obolibrary.org/obo/RO_0002442
#> 40 http://purl.obolibrary.org/obo/RO_0002441
#> 41 http://purl.obolibrary.org/obo/RO_0002623
#> 42 http://purl.obolibrary.org/obo/RO_0002622
#> 43 http://purl.obolibrary.org/obo/RO_0002619
#> 44 http://purl.obolibrary.org/obo/RO_0002618
#> 45 http://purl.obolibrary.org/obo/RO_0002321
#> 46 http://purl.obolibrary.org/obo/RO_0008506
#> 47 http://purl.obolibrary.org/obo/RO_0002801
#> 48 http://purl.obolibrary.org/obo/RO_0002437
#> 49 http://purl.obolibrary.org/obo/RO_0002220
# }
```
