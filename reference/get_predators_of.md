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
[`get_interactions()`](https://docs.ropensci.org/rglobi/reference/get_interactions.md),
[`get_interactions_by_taxa()`](https://docs.ropensci.org/rglobi/reference/get_interactions_by_taxa.md),
[`get_interactions_by_type()`](https://docs.ropensci.org/rglobi/reference/get_interactions_by_type.md),
[`get_prey_of()`](https://docs.ropensci.org/rglobi/reference/get_prey_of.md)

## Examples

``` r
# \donttest{
get_predators_of("Rattus rattus")
#>                   source_taxon_external_id source_taxon_name
#> 1                               EOL:328447     Rattus rattus
#> 2                               EOL:328447     Rattus rattus
#> 3                               EOL:328447     Rattus rattus
#> 4                               EOL:328447     Rattus rattus
#> 5                               EOL:328447     Rattus rattus
#> 6                               EOL:328447     Rattus rattus
#> 7                               EOL:328447     Rattus rattus
#> 8                               EOL:328447     Rattus rattus
#> 9                               EOL:328447     Rattus rattus
#> 10                              EOL:328447     Rattus rattus
#> 11                              EOL:328447     Rattus rattus
#> 12                              EOL:328447     Rattus rattus
#> 13                              EOL:328447     Rattus rattus
#> 14                              EOL:328447     Rattus rattus
#> 15                              EOL:328447     Rattus rattus
#> 16                              EOL:328447     Rattus rattus
#> 17                              EOL:328447     Rattus rattus
#> 18                              EOL:328447     Rattus rattus
#> 19                              EOL:328447     Rattus rattus
#> 20                              EOL:328447     Rattus rattus
#> 21                              EOL:328447     Rattus rattus
#> 22                              EOL:328447     Rattus rattus
#> 23                              EOL:328447     Rattus rattus
#> 24                              EOL:328447     Rattus rattus
#> 25                              EOL:328447     Rattus rattus
#> 26                              EOL:328447     Rattus rattus
#> 27                              EOL:328447     Rattus rattus
#> 28                              EOL:328447     Rattus rattus
#> 29                              EOL:328447     Rattus rattus
#> 30                              EOL:328447     Rattus rattus
#> 31                              EOL:328447     Rattus rattus
#> 32                              EOL:328447     Rattus rattus
#> 33                              EOL:328447     Rattus rattus
#> 34                              EOL:328447     Rattus rattus
#> 35                              EOL:328447     Rattus rattus
#> 36                              EOL:328447     Rattus rattus
#> 37                              EOL:328447     Rattus rattus
#> 38                              EOL:328447     Rattus rattus
#> 39                              EOL:328447     Rattus rattus
#> 40                              EOL:328447     Rattus rattus
#> 41                              EOL:328447     Rattus rattus
#> 42                              EOL:328447     Rattus rattus
#> 43                              EOL:328447     Rattus rattus
#> 44                              EOL:328447     Rattus rattus
#> 45                              EOL:328447     Rattus rattus
#> 46                              EOL:328447     Rattus rattus
#> 47                              EOL:328447     Rattus rattus
#> 48                              EOL:328447     Rattus rattus
#> 49                              EOL:328447     Rattus rattus
#> 50                              EOL:328447     Rattus rattus
#> 51                              EOL:328447     Rattus rattus
#> 52                              EOL:328447     Rattus rattus
#> 53                              EOL:328447     Rattus rattus
#> 54                              EOL:328447     Rattus rattus
#> 55                              EOL:328447     Rattus rattus
#> 56                              EOL:328447     Rattus rattus
#> 57                              EOL:328447     Rattus rattus
#> 58                              EOL:328447     Rattus rattus
#> 59                              EOL:328447     Rattus rattus
#> 60                              EOL:328447     Rattus rattus
#> 61                              EOL:328447     Rattus rattus
#> 62                              EOL:328447     Rattus rattus
#> 63                              EOL:328447     Rattus rattus
#> 64                              EOL:328447     Rattus rattus
#> 65                              EOL:328447     Rattus rattus
#> 66                              EOL:328447     Rattus rattus
#> 67                              EOL:328447     Rattus rattus
#> 68                              EOL:328447     Rattus rattus
#> 69                              EOL:328447     Rattus rattus
#> 70                              EOL:328447     Rattus rattus
#> 71                              EOL:328447     Rattus rattus
#> 72                              EOL:328447     Rattus rattus
#> 73                              EOL:328447     Rattus rattus
#> 74 FB:kcwQJVpfCqNSSRW8O/OxgBDnWMoAAYBikA==              <NA>
#>                                                                                                                                                                                                                                                                                                                                                                                                                       source_taxon_path
#> 1  Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 2  Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 3  Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 4  Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 5  Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 6  Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 7  Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 8  Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 9  Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 10 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 11 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 12 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 13 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 14 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 15 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 16 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 17 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 18 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 19 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 20 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 21 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 22 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 23 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 24 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 25 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 26 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 27 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 28 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 29 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 30 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 31 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 32 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 33 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 34 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 35 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 36 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 37 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 38 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 39 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 40 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 41 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 42 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 43 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 44 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 45 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 46 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 47 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 48 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 49 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 50 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 51 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 52 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 53 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 54 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 55 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 56 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 57 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 58 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 59 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 60 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 61 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 62 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 63 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 64 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 65 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 66 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 67 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 68 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 69 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 70 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 71 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 72 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 73 Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 74                                                                                                                                                                                                                                                                                                                                                                                                                                 <NA>
#>    source_specimen_life_stage interaction_type target_taxon_external_id
#> 1                          NA     preyedUponBy                COL:3DXV3
#> 2                          NA     preyedUponBy                COL:7F2KB
#> 3                          NA     preyedUponBy                COL:3SBPN
#> 4                          NA     preyedUponBy             WORMS:159742
#> 5                          NA     preyedUponBy              NCBI:201439
#> 6                          NA     preyedUponBy                 COL:YH2R
#> 7                          NA     preyedUponBy                COL:44QY4
#> 8                          NA     preyedUponBy               EOL:328684
#> 9                          NA     preyedUponBy                COL:7G2VS
#> 10                         NA     preyedUponBy                COL:44QYC
#> 11                         NA     preyedUponBy                COL:5BJ7S
#> 12                         NA     preyedUponBy                COL:59ZVQ
#> 13                         NA     preyedUponBy             GBIF:2439223
#> 14                         NA     preyedUponBy               EOL:328095
#> 15                         NA     preyedUponBy                COL:3DXW2
#> 16                         NA     preyedUponBy                 COL:YNHG
#> 17                         NA     preyedUponBy                 COL:QLX7
#> 18                         NA     preyedUponBy                COL:6866L
#> 19                         NA     preyedUponBy              EOL:1055888
#> 20                         NA     preyedUponBy               EOL:791987
#> 21                         NA     preyedUponBy                 COL:LXKX
#> 22                         NA     preyedUponBy                 COL:M7W3
#> 23                         NA     preyedUponBy                COL:6TDCW
#> 24                         NA     preyedUponBy              WD:Q1860532
#> 25                         NA     preyedUponBy                COL:5XQT6
#> 26                         NA     preyedUponBy               NCBI:35670
#> 27                         NA     preyedUponBy               EOL:790890
#> 28                         NA     preyedUponBy              NCBI:461325
#> 29                         NA     preyedUponBy                COL:6FQT3
#> 30                         NA     preyedUponBy                COL:45KXQ
#> 31                         NA     preyedUponBy                COL:4NCXP
#> 32                         NA     preyedUponBy                COL:4P4LY
#> 33                         NA     preyedUponBy                 COL:LXL7
#> 34                         NA     preyedUponBy                 COL:TZLD
#> 35                         NA     preyedUponBy                COL:5WNGD
#> 36                         NA     preyedUponBy               EOL:795321
#> 37                         NA     preyedUponBy                COL:7HGRD
#> 38                         NA     preyedUponBy                 COL:ZPBS
#> 39                         NA     preyedUponBy               WD:Q744773
#> 40                         NA     preyedUponBy                 no:match
#> 41                         NA     preyedUponBy              WD:Q2908902
#> 42                         NA     preyedUponBy             EOL:47046792
#> 43                         NA     preyedUponBy               EOL:796012
#> 44                         NA     preyedUponBy               WD:Q727428
#> 45                         NA     preyedUponBy                COL:38YJ8
#> 46                         NA     preyedUponBy                COL:CTVJX
#> 47                         NA     preyedUponBy                COL:3YXDW
#> 48                         NA     preyedUponBy                COL:5WTTW
#> 49                         NA     preyedUponBy                 COL:YNHD
#> 50                         NA     preyedUponBy                COL:59ZVV
#> 51                         NA     preyedUponBy                COL:3XQPW
#> 52                         NA     preyedUponBy                COL:69669
#> 53                         NA     preyedUponBy                COL:6DZ3D
#> 54                         NA     preyedUponBy              EOL:2774383
#> 55                         NA     preyedUponBy                COL:3DTGW
#> 56                         NA     preyedUponBy                COL:BNKZR
#> 57                         NA     preyedUponBy                COL:7JR74
#> 58                         NA     preyedUponBy                COL:7L6KP
#> 59                         NA     preyedUponBy                COL:485KR
#> 60                         NA     preyedUponBy               WD:Q974220
#> 61                         NA     preyedUponBy                 COL:NKTR
#> 62                         NA     preyedUponBy                COL:5LSBN
#> 63                         NA     preyedUponBy                COL:5BSG3
#> 64                         NA     preyedUponBy                COL:3S7BH
#> 65                         NA     preyedUponBy                COL:7DTJY
#> 66                         NA     preyedUponBy                COL:33SX2
#> 67                         NA     preyedUponBy                COL:CVW5J
#> 68                         NA     preyedUponBy                 COL:NKTJ
#> 69                         NA     preyedUponBy                COL:47FJS
#> 70                         NA     preyedUponBy                 COL:GCHR
#> 71                         NA     preyedUponBy                 COL:QLXL
#> 72                         NA     preyedUponBy                COL:3DTFR
#> 73                         NA     preyedUponBy               EOL:328447
#> 74                         NA             <NA>                     <NA>
#>                target_taxon_name
#> 1                    Felis catus
#> 2                   Ursus arctos
#> 3               Larus argentatus
#> 4                  Bubulcus ibis
#> 5            Zamenis longissimus
#> 6            Coronella austriaca
#> 7                Mustela nivalis
#> 8       Nyctereutes procyonoides
#> 9              Vespula germanica
#> 10              Mustela putorius
#> 11                  Vipera aspis
#> 12                     Tyto alba
#> 13                        Rattus
#> 14               Genetta genetta
#> 15              Felis silvestris
#> 16                  Corvus corax
#> 17                  Canis aureus
#> 18                     Asio otus
#> 19  Madagascarophis meridionalis
#> 20                 Liasis fuscus
#> 21                Bitis arietans
#> 22              Boaedon lineatus
#> 23           Ovophis okinavensis
#> 24            Rhinechis scalaris
#> 25        Chilabothrus subflavus
#> 26                     Naja naja
#> 27           Pseudonaja textilis
#> 28            Antaresia stimsoni
#> 29            Epicrates cenchria
#> 30                    Naja nivea
#> 31        Psammophis mossambicus
#> 32           Pseudonaja nuchalis
#> 33                Bitis gabonica
#> 34      Chilabothrus strigilatus
#> 35             Boiga irregularis
#> 36        Hemorrhois hippocrepis
#> 37       Morelia spilota spilota
#> 38             Crotalus horridus
#> 39          Psammophis phillipsi
#> 40             Pseudohaje göldii
#> 41              Boiruna maculata
#> 42           Coluber mentovarius
#> 43    Borikenophis portoricensis
#> 44          Philodryas nattereri
#> 45               Elanus leucurus
#> 46              Circus hudsonius
#> 47                Megascops asio
#> 48                Buteo lineatus
#> 49         Corvus brachyrhynchos
#> 50                  Tyto furcata
#> 51       Malpolon monspessulanus
#> 52             Buteo jamaicensis
#> 53       Egretta novaehollandiae
#> 54                    Vertebrata
#> 55             Falco tinnunculus
#> 56 Larus dominicanus dominicanus
#> 57    Elanus leucurus majusculus
#> 58  Urocyon littoralis catalinae
#> 59         Nycticorax nycticorax
#> 60           Cracticus torquatus
#> 61              Bubo virginianus
#> 62       Vulpes vulpes crucigera
#> 63                 Vulpes vulpes
#> 64               Lanius collaris
#> 65      Urocyon cinereoargenteus
#> 66           Dacelo novaeguineae
#> 67                Astur cooperii
#> 68               Bubo scandiacus
#> 69                 Ninox boobook
#> 70                    Ardea alba
#> 71                   Canis lupus
#> 72                Falco berigora
#> 73                 Rattus rattus
#> 74                          <NA>
#>                                                                                                                                                                                                                                                                                                                                                                                                                             target_taxon_path
#> 1                                                                                                                                                                                                                                                   Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Carnivora | Feliformia | Felidae | Felinae | Felis | Felis catus
#> 2                                                                                                                                                                                                                                                            Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Carnivora | Caniformia | Ursidae | Ursus | Ursus arctos
#> 3                                                                                                                                                                                                                                                                                       Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Aves | Charadriiformes | Laridae | Larus | Larus argentatus
#> 4                                                                                                                                                                                                                                                                                                Biota | Animalia | Chordata | Vertebrata | Gnathostomata | Tetrapoda | Reptilia | Aves | Ciconiiformes | Ardeidae | Bubulcus | Bubulcus ibis
#> 5  root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Sauropsida | Sauria | Lepidosauria | Squamata | Bifurcata | Unidentata | Episquamata | Toxicofera | Serpentes | Colubroidea | Colubridae | Colubrinae | Zamenis | Zamenis longissimus
#> 6                                                                                                                                                                                                                                      Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Reptilia | Squamata | Serpentes | Alethinophidia | Colubridae | Colubrinae | Coronella | Coronella austriaca
#> 7                                                                                                                                                                                                                                       Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Carnivora | Caniformia | Mustelidae | Mustelinae | Mustela | Mustela nivalis
#> 8                                        Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Laurasiatheria | Scrotifera | Carnivora | Caniformia | Canidae | Nyctereutes | Nyctereutes procyonoides
#> 9                                                                                                                                                                                                                                                                                  Eukaryota | Animalia | Arthropoda | Hexapoda | Insecta | Hymenoptera | Apocrita | Aculeata | Vespoidea | Vespidae | Vespinae | Vespula | Vespula germanica
#> 10                                                                                                                                                                                                                                     Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Carnivora | Caniformia | Mustelidae | Mustelinae | Mustela | Mustela putorius
#> 11                                                                                                                                                                                                                                                 Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Reptilia | Squamata | Serpentes | Alethinophidia | Viperidae | Viperinae | Vipera | Vipera aspis
#> 12                                                                                                                                                                                                                                                                                   Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Aves | Strigiformes | Tytonidae | Tytoninae | Tyto | Tyto alba
#> 13                                                                                                                                                                                                                                                                                                                                                                               Animalia | Chordata | Mammalia | Rodentia | Muridae | Rattus
#> 14                                    Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Laurasiatheria | Scrotifera | Carnivora | Feliformia | Viverridae | Viverrinae | Genetta | Genetta genetta
#> 15                                                                                                                                                                                                                                             Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Carnivora | Feliformia | Felidae | Felinae | Felis | Felis silvestris
#> 16                                                                                                                                                                                                                                                                                          Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Aves | Passeriformes | Corvidae | Corvus | Corvus corax
#> 17                                                                                                                                                                                                                                                           Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Carnivora | Caniformia | Canidae | Canis | Canis aureus
#> 18                                                                                                                                                                                                                                                                                   Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Aves | Strigiformes | Strigidae | Striginae | Asio | Asio otus
#> 19                                                             Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Reptilia | Diapsida | Lepidosauromorpha | Lepidosauria | Squamata | Serpentes | Alethinophidia | Lamprophiidae | Pseudoxyrhophiinae | Madagascarophis | Madagascarophis meridionalis
#> 20                                                                                                             Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Reptilia | Diapsida | Lepidosauromorpha | Lepidosauria | Squamata | Serpentes | Alethinophidia | Pythonidae | Liasis | Liasis fuscus
#> 21                                                                                                                                                                                                                                                Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Reptilia | Squamata | Serpentes | Alethinophidia | Viperidae | Viperinae | Bitis | Bitis arietans
#> 22                                                                                                                                                                                                                                                    Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Reptilia | Squamata | Serpentes | Alethinophidia | Lamprophiidae | Boaedon | Boaedon lineatus
#> 23                                                                                                                                                                                                                                        Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Reptilia | Squamata | Serpentes | Alethinophidia | Viperidae | Crotalinae | Ovophis | Ovophis okinavensis
#> 24                                                                                                                                                                                                                                                                                                                Ophidia | Serpentes | Alethinophidia | Caenophidia | Colubroidea | Colubridae | Colubrinae | Rhinechis | Rhinechis scalaris
#> 25                                                                                                                                                                                                                                       Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Reptilia | Squamata | Serpentes | Alethinophidia | Boidae | Boinae | Chilabothrus | Chilabothrus subflavus
#> 26                  root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Sauropsida | Sauria | Lepidosauria | Squamata | Bifurcata | Unidentata | Episquamata | Toxicofera | Serpentes | Colubroidea | Elapidae | Elapinae | Naja | Naja naja
#> 27                                                                                      Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Reptilia | Diapsida | Lepidosauromorpha | Lepidosauria | Squamata | Serpentes | Alethinophidia | Elapidae | Hydrophiinae | Pseudonaja | Pseudonaja textilis
#> 28              root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Sauropsida | Sauria | Lepidosauria | Squamata | Bifurcata | Unidentata | Episquamata | Toxicofera | Serpentes | Henophidia | Pythonidae | Antaresia | Antaresia stimsoni
#> 29                                                                                                                                                                                                                                              Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Reptilia | Squamata | Serpentes | Alethinophidia | Boidae | Boinae | Epicrates | Epicrates cenchria
#> 30                                                                                                                                                                                                                                                                  Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Reptilia | Squamata | Serpentes | Alethinophidia | Elapidae | Naja | Naja nivea
#> 31                                                                                                                                                                                                                                           Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Reptilia | Squamata | Serpentes | Alethinophidia | Psammophiidae | Psammophis | Psammophis mossambicus
#> 32                                                                                                                                                                                                                                    Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Reptilia | Squamata | Serpentes | Alethinophidia | Elapidae | Hydrophiinae | Pseudonaja | Pseudonaja nuchalis
#> 33                                                                                                                                                                                                                                                Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Reptilia | Squamata | Serpentes | Alethinophidia | Viperidae | Viperinae | Bitis | Bitis gabonica
#> 34                                                                                                                                                                                                                                     Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Reptilia | Squamata | Serpentes | Alethinophidia | Boidae | Boinae | Chilabothrus | Chilabothrus strigilatus
#> 35                                                                                                                                                                                                                                           Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Reptilia | Squamata | Serpentes | Alethinophidia | Colubridae | Colubrinae | Boiga | Boiga irregularis
#> 36                                                                                   Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Reptilia | Diapsida | Lepidosauromorpha | Lepidosauria | Squamata | Serpentes | Alethinophidia | Colubridae | Colubrinae | Hemorrhois | Hemorrhois hippocrepis
#> 37                                                                                                                                                                                                                              Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Reptilia | Squamata | Serpentes | Alethinophidia | Pythonidae | Morelia | Morelia spilota | Morelia spilota spilota
#> 38                                                                                                                                                                                                                                         Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Reptilia | Squamata | Serpentes | Alethinophidia | Viperidae | Crotalinae | Crotalus | Crotalus horridus
#> 39                                                                                                                                                                                                                                                                                                                     Ophidia | Serpentes | Alethinophidia | Caenophidia | Lamprophiidae | Psammophiinae | Psammophis | Psammophis phillipsi
#> 40                                                                                                                                                                                                                                                                                                                                                                                                                                       <NA>
#> 41                                                                                                                                                                                                                                                                                                                    Ophidia | Serpentes | Alethinophidia | Caenophidia | Colubroidea | Colubridae | Dipsadinae | Boiruna | Boiruna maculata
#> 42                                                                                         Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Reptilia | Diapsida | Lepidosauromorpha | Lepidosauria | Squamata | Serpentes | Alethinophidia | Colubridae | Colubrinae | Coluber | Coluber mentovarius
#> 43                                                                             Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Reptilia | Diapsida | Lepidosauromorpha | Lepidosauria | Squamata | Serpentes | Alethinophidia | Colubridae | Dipsadinae | Borikenophis | Borikenophis portoricensis
#> 44                                                                                                                                                                                                                                                                                                             Ophidia | Serpentes | Alethinophidia | Caenophidia | Colubroidea | Colubridae | Dipsadinae | Philodryas | Philodryas nattereri
#> 45                                                                                                                                                                                                                                                                                 Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Aves | Accipitriformes | Accipitridae | Elanus | Elanus leucurus
#> 46                                                                                                                                                                                                                                                                                Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Aves | Accipitriformes | Accipitridae | Circus | Circus hudsonius
#> 47                                                                                                                                                                                                                                                                         Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Aves | Strigiformes | Strigidae | Striginae | Megascops | Megascops asio
#> 48                                                                                                                                                                                                                                                                                   Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Aves | Accipitriformes | Accipitridae | Buteo | Buteo lineatus
#> 49                                                                                                                                                                                                                                                                                 Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Aves | Passeriformes | Corvidae | Corvus | Corvus brachyrhynchos
#> 50                                                                                                                                                                                                                                                                                Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Aves | Strigiformes | Tytonidae | Tytoninae | Tyto | Tyto furcata
#> 51                                                                                                                                                                                                                                            Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Reptilia | Squamata | Serpentes | Alethinophidia | Psammophiidae | Malpolon | Malpolon monspessulanus
#> 52                                                                                                                                                                                                                                                                                Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Aves | Accipitriformes | Accipitridae | Buteo | Buteo jamaicensis
#> 53                                                                                                                                                                                                                                                                             Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Aves | Pelecaniformes | Ardeidae | Egretta | Egretta novaehollandiae
#> 54                                                                                                                                                                                                                                                                                                                         Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata
#> 55                                                                                                                                                                                                                                                                       Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Aves | Falconiformes | Falconidae | Falconinae | Falco | Falco tinnunculus
#> 56                                                                                                                                                                                                                                                     Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Aves | Charadriiformes | Laridae | Larus | Larus dominicanus | Larus dominicanus dominicanus
#> 57                                                                                                                                                                                                                                                    Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Aves | Accipitriformes | Accipitridae | Elanus | Elanus leucurus | Elanus leucurus majusculus
#> 58                                                                                                                                                                                                                    Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Carnivora | Caniformia | Canidae | Urocyon | Urocyon littoralis | Urocyon littoralis catalinae
#> 59                                                                                                                                                                                                                                                                            Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Aves | Pelecaniformes | Ardeidae | Nycticorax | Nycticorax nycticorax
#> 60                                                                                                                                                                                                                                                                                                                          Australavis | Eufalconimorphae | Psittacopasserae | Passeriformes | Cracticidae | Cracticus | Cracticus torquatus
#> 61                                                                                                                                                                                                                                                                            Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Aves | Strigiformes | Strigidae | Striginae | Bubo | Bubo virginianus
#> 62                                                                                                                                                                                                                               Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Carnivora | Caniformia | Canidae | Vulpes | Vulpes vulpes | Vulpes vulpes crucigera
#> 63                                                                                                                                                                                                                                                         Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Carnivora | Caniformia | Canidae | Vulpes | Vulpes vulpes
#> 64                                                                                                                                                                                                                                                                                       Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Aves | Passeriformes | Laniidae | Lanius | Lanius collaris
#> 65                                                                                                                                                                                                                                             Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Carnivora | Caniformia | Canidae | Urocyon | Urocyon cinereoargenteus
#> 66                                                                                                                                                                                                                                                                  Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Aves | Coraciiformes | Alcedinidae | Halcyoninae | Dacelo | Dacelo novaeguineae
#> 67                                                                                                                                                                                                                                                                                   Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Aves | Accipitriformes | Accipitridae | Astur | Astur cooperii
#> 68                                                                                                                                                                                                                                                                             Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Aves | Strigiformes | Strigidae | Striginae | Bubo | Bubo scandiacus
#> 69                                                                                                                                                                                                                                                                              Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Aves | Strigiformes | Strigidae | Ninoxinae | Ninox | Ninox boobook
#> 70                                                                                                                                                                                                                                                                                            Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Aves | Pelecaniformes | Ardeidae | Ardea | Ardea alba
#> 71                                                                                                                                                                                                                                                            Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Carnivora | Caniformia | Canidae | Canis | Canis lupus
#> 72                                                                                                                                                                                                                                                                          Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Aves | Falconiformes | Falconidae | Falconinae | Falco | Falco berigora
#> 73       Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Glires | Rodentia | Mouse relatives | Myomorpha | Muroidea | Eumuroidea | Muridae | Murinae | Rattus | Rattus rattus
#> 74                                                                                                                                                                                                                                                                                                                                                                                                                                       <NA>
#>    target_specimen_life_stage latitude longitude study_citation
#> 1                          NA       NA        NA             NA
#> 2                          NA       NA        NA             NA
#> 3                          NA       NA        NA             NA
#> 4                          NA       NA        NA             NA
#> 5                          NA       NA        NA             NA
#> 6                          NA       NA        NA             NA
#> 7                          NA       NA        NA             NA
#> 8                          NA       NA        NA             NA
#> 9                          NA       NA        NA             NA
#> 10                         NA       NA        NA             NA
#> 11                         NA       NA        NA             NA
#> 12                         NA       NA        NA             NA
#> 13                         NA       NA        NA             NA
#> 14                         NA       NA        NA             NA
#> 15                         NA       NA        NA             NA
#> 16                         NA       NA        NA             NA
#> 17                         NA       NA        NA             NA
#> 18                         NA       NA        NA             NA
#> 19                         NA       NA        NA             NA
#> 20                         NA       NA        NA             NA
#> 21                         NA       NA        NA             NA
#> 22                         NA       NA        NA             NA
#> 23                         NA       NA        NA             NA
#> 24                         NA       NA        NA             NA
#> 25                         NA       NA        NA             NA
#> 26                         NA       NA        NA             NA
#> 27                         NA       NA        NA             NA
#> 28                         NA       NA        NA             NA
#> 29                         NA       NA        NA             NA
#> 30                         NA       NA        NA             NA
#> 31                         NA       NA        NA             NA
#> 32                         NA       NA        NA             NA
#> 33                         NA       NA        NA             NA
#> 34                         NA       NA        NA             NA
#> 35                         NA       NA        NA             NA
#> 36                         NA       NA        NA             NA
#> 37                         NA       NA        NA             NA
#> 38                         NA       NA        NA             NA
#> 39                         NA       NA        NA             NA
#> 40                         NA       NA        NA             NA
#> 41                         NA       NA        NA             NA
#> 42                         NA       NA        NA             NA
#> 43                         NA       NA        NA             NA
#> 44                         NA       NA        NA             NA
#> 45                         NA       NA        NA             NA
#> 46                         NA       NA        NA             NA
#> 47                         NA       NA        NA             NA
#> 48                         NA       NA        NA             NA
#> 49                         NA       NA        NA             NA
#> 50                         NA       NA        NA             NA
#> 51                         NA       NA        NA             NA
#> 52                         NA       NA        NA             NA
#> 53                         NA       NA        NA             NA
#> 54                         NA       NA        NA             NA
#> 55                         NA       NA        NA             NA
#> 56                         NA       NA        NA             NA
#> 57                         NA       NA        NA             NA
#> 58                         NA       NA        NA             NA
#> 59                         NA       NA        NA             NA
#> 60                         NA       NA        NA             NA
#> 61                         NA       NA        NA             NA
#> 62                         NA       NA        NA             NA
#> 63                         NA       NA        NA             NA
#> 64                         NA       NA        NA             NA
#> 65                         NA       NA        NA             NA
#> 66                         NA       NA        NA             NA
#> 67                         NA       NA        NA             NA
#> 68                         NA       NA        NA             NA
#> 69                         NA       NA        NA             NA
#> 70                         NA       NA        NA             NA
#> 71                         NA       NA        NA             NA
#> 72                         NA       NA        NA             NA
#> 73                         NA       NA        NA             NA
#> 74                         NA       NA        NA             NA
#>    study_source_citation
#> 1                     NA
#> 2                     NA
#> 3                     NA
#> 4                     NA
#> 5                     NA
#> 6                     NA
#> 7                     NA
#> 8                     NA
#> 9                     NA
#> 10                    NA
#> 11                    NA
#> 12                    NA
#> 13                    NA
#> 14                    NA
#> 15                    NA
#> 16                    NA
#> 17                    NA
#> 18                    NA
#> 19                    NA
#> 20                    NA
#> 21                    NA
#> 22                    NA
#> 23                    NA
#> 24                    NA
#> 25                    NA
#> 26                    NA
#> 27                    NA
#> 28                    NA
#> 29                    NA
#> 30                    NA
#> 31                    NA
#> 32                    NA
#> 33                    NA
#> 34                    NA
#> 35                    NA
#> 36                    NA
#> 37                    NA
#> 38                    NA
#> 39                    NA
#> 40                    NA
#> 41                    NA
#> 42                    NA
#> 43                    NA
#> 44                    NA
#> 45                    NA
#> 46                    NA
#> 47                    NA
#> 48                    NA
#> 49                    NA
#> 50                    NA
#> 51                    NA
#> 52                    NA
#> 53                    NA
#> 54                    NA
#> 55                    NA
#> 56                    NA
#> 57                    NA
#> 58                    NA
#> 59                    NA
#> 60                    NA
#> 61                    NA
#> 62                    NA
#> 63                    NA
#> 64                    NA
#> 65                    NA
#> 66                    NA
#> 67                    NA
#> 68                    NA
#> 69                    NA
#> 70                    NA
#> 71                    NA
#> 72                    NA
#> 73                    NA
#> 74                    NA
get_predators_of("Primates")
#>                    source_taxon_external_id
#> 1                                EOL:313665
#> 2                                 COL:3WWNQ
#> 3                                 COL:3WWNQ
#> 4                                  COL:6DGR
#> 5                                  COL:6DGR
#> 6                                  COL:6DGR
#> 7                                  COL:6DGR
#> 8                                 COL:6MB3T
#> 9                                 COL:6MB3T
#> 10                                COL:6MB3T
#> 11                                COL:6MB3T
#> 12                                COL:6MB3T
#> 13                                COL:6MB3T
#> 14                                COL:6MB3T
#> 15                                COL:6MB3T
#> 16                                COL:6MB3T
#> 17                                COL:6MB3T
#> 18                                COL:6MB3T
#> 19                                COL:6MB3T
#> 20                                COL:6MB3T
#> 21                                COL:6MB3T
#> 22                                COL:6MB3T
#> 23                                COL:6MB3T
#> 24                                COL:6MB3T
#> 25                                COL:6MB3T
#> 26                                COL:6MB3T
#> 27                                COL:6MB3T
#> 28                                NCBI:9541
#> 29                                NCBI:9541
#> 30                                NCBI:9541
#> 31                                NCBI:9541
#> 32                                COL:697NS
#> 33                                COL:3F2DM
#> 34                                COL:3WWNK
#> 35                                COL:4C92G
#> 36                                 COL:SSTF
#> 37                                 COL:J8P6
#> 38                                COL:57SD8
#> 39                              NCBI:118643
#> 40                              NCBI:118643
#> 41                                 COL:5HYC
#> 42                                 COL:5HYC
#> 43                                 COL:5HYC
#> 44                                 COL:5HYC
#> 45                                 COL:5HYC
#> 46                                 COL:5HYC
#> 47                                 COL:5HYC
#> 48                                 COL:5HYC
#> 49                                 COL:5HYC
#> 50                                 COL:5HYC
#> 51                                 COL:5HYC
#> 52                                 COL:5HYC
#> 53                                 COL:5HYC
#> 54                                 COL:5HYC
#> 55                                 COL:5HYC
#> 56                                 COL:5HYC
#> 57                                COL:4CKZP
#> 58                                COL:4CKZP
#> 59                                COL:69VWT
#> 60                             GBIF:2436613
#> 61                                 COL:STFG
#> 62                                 COL:STFG
#> 63                                 COL:6D2G
#> 64                                 COL:6D2G
#> 65                                 COL:6D2G
#> 66                                 COL:6D2G
#> 67                               EOL:311211
#> 68                              EOL:2925214
#> 69                               EOL:310782
#> 70                              EOL:2925671
#> 71                              EOL:2925671
#> 72                               EOL:128444
#> 73                               EOL:310623
#> 74                               EOL:981572
#> 75                               EOL:323901
#> 76                               EOL:323901
#> 77                               EOL:323901
#> 78                               EOL:323901
#> 79                               EOL:128439
#> 80                              EOL:1010638
#> 81                               EOL:324404
#> 82                               EOL:324404
#> 83                               EOL:324404
#> 84                               EOL:326525
#> 85                               EOL:326525
#> 86                                 EOL:1657
#> 87                                 EOL:1657
#> 88                                 EOL:1657
#> 89                                 EOL:1657
#> 90                                 EOL:1657
#> 91                                 EOL:1657
#> 92                                 EOL:1657
#> 93                                 EOL:1657
#> 94                                 EOL:1657
#> 95                                 EOL:1657
#> 96                                 EOL:1657
#> 97                                EOL:39321
#> 98                                COL:636X2
#> 99                                COL:636X2
#> 100                               COL:636X2
#> 101                               COL:636X2
#> 102                               COL:636X2
#> 103                               COL:636X2
#> 104                               COL:636X2
#> 105                               COL:636X2
#> 106                              NCBI:30615
#> 107                               NCBI:9569
#> 108                               NCBI:9569
#> 109                                COL:78S4
#> 110                                COL:78S4
#> 111                                COL:78S4
#> 112                                COL:78S4
#> 113                                COL:78S4
#> 114                                COL:78S4
#> 115                                COL:78S4
#> 116                                COL:78S4
#> 117                                COL:78S4
#> 118                                COL:78S4
#> 119                                COL:78S4
#> 120                                COL:78S4
#> 121                                COL:78S4
#> 122                                COL:78S4
#> 123                                COL:78S4
#> 124                                COL:78S4
#> 125                              WD:Q463395
#> 126                              WD:Q463395
#> 127                              WD:Q463395
#> 128                              WD:Q463395
#> 129                               NCBI:9498
#> 130                               NCBI:9498
#> 131                               NCBI:9498
#> 132                               NCBI:9498
#> 133                               NCBI:9498
#> 134                               NCBI:9498
#> 135                             NCBI:314295
#> 136                                COL:6QFS
#> 137                               NCBI:9599
#> 138                               NCBI:9599
#> 139                               NCBI:9599
#> 140                             NCBI:121123
#> 141                             NCBI:392815
#> 142                             NCBI:392815
#> 143                             NCBI:392815
#> 144                             NCBI:392815
#> 145                             NCBI:392815
#> 146                             NCBI:392815
#> 147                             NCBI:392815
#> 148                             NCBI:392815
#> 149                             NCBI:392815
#> 150                               NCBI:9445
#> 151                               NCBI:9445
#> 152                               NCBI:9445
#> 153                               NCBI:9445
#> 154                               NCBI:9445
#> 155                               NCBI:9445
#> 156                               NCBI:9445
#> 157                               NCBI:9445
#> 158                               NCBI:9445
#> 159                               NCBI:9445
#> 160                               NCBI:9511
#> 161                               COL:S43YF
#> 162                              NCBI:83281
#> 163                              NCBI:13556
#> 164                             NCBI:379532
#> 165                             NCBI:379532
#> 166                              NCBI:78451
#> 167                               NCBI:9595
#> 168                               NCBI:9595
#> 169                              NCBI:30593
#> 170                              NCBI:30593
#> 171                              NCBI:30593
#> 172                             NCBI:767357
#> 173                               EOL:15096
#> 174                              NCBI:46359
#> 175                              NCBI:46359
#> 176                             NCBI:402888
#> 177                             NCBI:402888
#> 178                            NCBI:1868482
#> 179                              NCBI:40297
#> 180                              NCBI:13513
#> 181                            NCBI:1137476
#> 182                            NCBI:1137476
#> 183                              NCBI:30594
#> 184                            NCBI:1284215
#> 185                             NCBI:132108
#> 186                            NCBI:1137048
#> 187                              NCBI:54181
#> 188                            NCBI:1532884
#> 189                                COL:75SR
#> 190                               COL:4QNHG
#> 191                               COL:34B7X
#> 192                               COL:7JLSJ
#> 193                               COL:7JM4K
#> 194                               COL:5GC2Z
#> 195                               COL:5GC3D
#> 196                               COL:5GC32
#> 197                               COL:5K6DT
#> 198                                 COL:KPP
#> 199                               COL:5GC47
#> 200                               COL:5FHSL
#> 201                             NCBI:867370
#> 202                             NCBI:867370
#> 203                               COL:6LBGW
#> 204 FB:kcwQJVpfCqNSSRW8O/OxgBDnWMoAAYBikA==
#>                          source_taxon_name
#> 1                      Cercopithecus mitis
#> 2                           Macaca mulatta
#> 3                           Macaca mulatta
#> 4                                    Papio
#> 5                                    Papio
#> 6                                    Papio
#> 7                                    Papio
#> 8                             Homo sapiens
#> 9                             Homo sapiens
#> 10                            Homo sapiens
#> 11                            Homo sapiens
#> 12                            Homo sapiens
#> 13                            Homo sapiens
#> 14                            Homo sapiens
#> 15                            Homo sapiens
#> 16                            Homo sapiens
#> 17                            Homo sapiens
#> 18                            Homo sapiens
#> 19                            Homo sapiens
#> 20                            Homo sapiens
#> 21                            Homo sapiens
#> 22                            Homo sapiens
#> 23                            Homo sapiens
#> 24                            Homo sapiens
#> 25                            Homo sapiens
#> 26                            Homo sapiens
#> 27                            Homo sapiens
#> 28                     Macaca fascicularis
#> 29                     Macaca fascicularis
#> 30                     Macaca fascicularis
#> 31                     Macaca fascicularis
#> 32                      Callithrix jacchus
#> 33                     Galago senegalensis
#> 34                          Macaca leonina
#> 35                         Pan troglodytes
#> 36                    Cercocebus torquatus
#> 37                        Ateles geoffroyi
#> 38                Trachypithecus cristatus
#> 39                           Ateles chamek
#> 40                           Ateles chamek
#> 41                                  Macaca
#> 42                                  Macaca
#> 43                                  Macaca
#> 44                                  Macaca
#> 45                                  Macaca
#> 46                                  Macaca
#> 47                                  Macaca
#> 48                                  Macaca
#> 49                                  Macaca
#> 50                                  Macaca
#> 51                                  Macaca
#> 52                                  Macaca
#> 53                                  Macaca
#> 54                                  Macaca
#> 55                                  Macaca
#> 56                                  Macaca
#> 57                           Papio ursinus
#> 58                           Papio ursinus
#> 59                 Chlorocebus pygerythrus
#> 60                           Macaca sinica
#> 61                      Cercopithecus mona
#> 62                      Cercopithecus mona
#> 63                                     Pan
#> 64                                     Pan
#> 65                                     Pan
#> 66                                     Pan
#> 67                     Galagoides demidoff
#> 68                            Papio anubis
#> 69                  Mandrillus leucophaeus
#> 70                            Pongo abelii
#> 71                            Pongo abelii
#> 72                         Colobus guereza
#> 73                  Semnopithecus entellus
#> 74                 Cercopithecus nictitans
#> 75                      Saguinus imperator
#> 76                      Saguinus imperator
#> 77                      Saguinus imperator
#> 78                      Saguinus imperator
#> 79                  Cercopithecus pogonias
#> 80                 Cercopithecus neglectus
#> 81                      Microcebus murinus
#> 82                      Microcebus murinus
#> 83                      Microcebus murinus
#> 84                          Eulemur fulvus
#> 85                          Eulemur fulvus
#> 86                         Cercopithecidae
#> 87                         Cercopithecidae
#> 88                         Cercopithecidae
#> 89                         Cercopithecidae
#> 90                         Cercopithecidae
#> 91                         Cercopithecidae
#> 92                         Cercopithecidae
#> 93                         Cercopithecidae
#> 94                         Cercopithecidae
#> 95                         Cercopithecidae
#> 96                         Cercopithecidae
#> 97                              Microcebus
#> 98                                    Homo
#> 99                                    Homo
#> 100                                   Homo
#> 101                                   Homo
#> 102                                   Homo
#> 103                                   Homo
#> 104                                   Homo
#> 105                                   Homo
#> 106                         Cheirogaleidae
#> 107                              Colobinae
#> 108                              Colobinae
#> 109                          Rhinopithecus
#> 110                          Rhinopithecus
#> 111                          Rhinopithecus
#> 112                          Rhinopithecus
#> 113                          Rhinopithecus
#> 114                          Rhinopithecus
#> 115                          Rhinopithecus
#> 116                          Rhinopithecus
#> 117                          Rhinopithecus
#> 118                          Rhinopithecus
#> 119                          Rhinopithecus
#> 120                          Rhinopithecus
#> 121                          Rhinopithecus
#> 122                          Rhinopithecus
#> 123                          Rhinopithecus
#> 124                          Rhinopithecus
#> 125                               Atelidae
#> 126                               Atelidae
#> 127                               Atelidae
#> 128                               Atelidae
#> 129                                Cebidae
#> 130                                Cebidae
#> 131                                Cebidae
#> 132                                Cebidae
#> 133                                Cebidae
#> 134                                Cebidae
#> 135                             Hominoidea
#> 136                           Piliocolobus
#> 137                                  Pongo
#> 138                                  Pongo
#> 139                                  Pongo
#> 140                          Alouatta sara
#> 141                            Chlorocebus
#> 142                            Chlorocebus
#> 143                            Chlorocebus
#> 144                            Chlorocebus
#> 145                            Chlorocebus
#> 146                            Chlorocebus
#> 147                            Chlorocebus
#> 148                            Chlorocebus
#> 149                            Chlorocebus
#> 150                              Lemuridae
#> 151                              Lemuridae
#> 152                              Lemuridae
#> 153                              Lemuridae
#> 154                              Lemuridae
#> 155                              Lemuridae
#> 156                              Lemuridae
#> 157                              Lemuridae
#> 158                              Lemuridae
#> 159                              Lemuridae
#> 160                             Ateles sp.
#> 161                          Protopithecus
#> 162                    Propithecus diadema
#> 163                              Hapalemur
#> 164                  Propithecus coquereli
#> 165                  Propithecus coquereli
#> 166                   Presbytis melalophos
#> 167                Gorilla gorilla gorilla
#> 168                Gorilla gorilla gorilla
#> 169                            Brachyteles
#> 170                            Brachyteles
#> 171                            Brachyteles
#> 172                         Lagothrix cana
#> 173                         Trachypithecus
#> 174               Gorilla beringei graueri
#> 175               Gorilla beringei graueri
#> 176                         Macaca munzala
#> 177                         Macaca munzala
#> 178                       Carlito syrichta
#> 179                              Galagidae
#> 180                                Eulemur
#> 181 Cercopithecus albogularis erythrarchus
#> 182 Cercopithecus albogularis erythrarchus
#> 183                Brachyteles arachnoides
#> 184              Chlorocebus djamdjamensis
#> 185                     Avahi occidentalis
#> 186                    Cercopithecus dryas
#> 187                Trachypithecus obscurus
#> 188                                Sapajus
#> 189                              Pygathrix
#> 190                     Pygathrix nigripes
#> 191           Daubentonia madagascariensis
#> 192    Chlorocebus pygerythrus rufoviridis
#> 193    Chlorocebus pygerythrus pygerythrus
#> 194          Cercopithecus cephus cephodes
#> 195    Cercopithecus erythrotis erythrotis
#> 196            Cercopithecus cephus cephus
#> 197                Papio ursinus griseipes
#> 198                         Cercopithecini
#> 199         Cercopithecus mitis stuhlmanni
#> 200          Allochrocebus preussi preussi
#> 201              Cercopithecus albogularis
#> 202              Cercopithecus albogularis
#> 203                 Hapalemur meridionalis
#> 204                                   <NA>
#>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        source_taxon_path
#> 1                          Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Haplorrhini | Anthropoidea | Catarrhini | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Cercopithecini | Cercopithecus | Cercopithecus mitis
#> 2                                                                                                                                                                                                                                                             Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Papionini | Macaca | Macaca mulatta
#> 3                                                                                                                                                                                                                                                             Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Papionini | Macaca | Macaca mulatta
#> 4                                                                                                                                                                                                                                                                               Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Papionini | Papio
#> 5                                                                                                                                                                                                                                                                               Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Papionini | Papio
#> 6                                                                                                                                                                                                                                                                               Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Papionini | Papio
#> 7                                                                                                                                                                                                                                                                               Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Papionini | Papio
#> 8                                                                                                                                                                                                                                                                                               Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 9                                                                                                                                                                                                                                                                                               Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 10                                                                                                                                                                                                                                                                                              Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 11                                                                                                                                                                                                                                                                                              Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 12                                                                                                                                                                                                                                                                                              Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 13                                                                                                                                                                                                                                                                                              Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 14                                                                                                                                                                                                                                                                                              Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 15                                                                                                                                                                                                                                                                                              Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 16                                                                                                                                                                                                                                                                                              Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 17                                                                                                                                                                                                                                                                                              Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 18                                                                                                                                                                                                                                                                                              Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 19                                                                                                                                                                                                                                                                                              Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 20                                                                                                                                                                                                                                                                                              Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 21                                                                                                                                                                                                                                                                                              Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 22                                                                                                                                                                                                                                                                                              Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 23                                                                                                                                                                                                                                                                                              Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 24                                                                                                                                                                                                                                                                                              Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 25                                                                                                                                                                                                                                                                                              Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 26                                                                                                                                                                                                                                                                                              Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 27                                                                                                                                                                                                                                                                                              Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 28                                                        root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Macaca | Macaca fascicularis
#> 29                                                        root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Macaca | Macaca fascicularis
#> 30                                                        root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Macaca | Macaca fascicularis
#> 31                                                        root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Macaca | Macaca fascicularis
#> 32                                                                                                                                                                                                                                                                                                      Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Callitrichidae | Callithrix | Callithrix jacchus
#> 33                                                                                                                                                                                                                                                                                                           Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Strepsirrhini | Lorisiformes | Galagidae | Galago | Galago senegalensis
#> 34                                                                                                                                                                                                                                                            Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Papionini | Macaca | Macaca leonina
#> 35                                                                                                                                                                                                                                                                                            Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Pan | Pan troglodytes
#> 36                                                                                                                                                                                                                                                  Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Papionini | Cercocebus | Cercocebus torquatus
#> 37                                                                                                                                                                                                                                                                                                       Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Atelidae | Atelinae | Ateles | Ateles geoffroyi
#> 38                                                                                                                                                                                                                                               Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Colobinae | Presbytini | Trachypithecus | Trachypithecus cristatus
#> 39                                                                                              root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Platyrrhini | Atelidae | Atelinae | Ateles | Ateles chamek
#> 40                                                                                              root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Platyrrhini | Atelidae | Atelinae | Ateles | Ateles chamek
#> 41                                                                                                                                                                                                                                                                             Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Papionini | Macaca
#> 42                                                                                                                                                                                                                                                                             Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Papionini | Macaca
#> 43                                                                                                                                                                                                                                                                             Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Papionini | Macaca
#> 44                                                                                                                                                                                                                                                                             Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Papionini | Macaca
#> 45                                                                                                                                                                                                                                                                             Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Papionini | Macaca
#> 46                                                                                                                                                                                                                                                                             Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Papionini | Macaca
#> 47                                                                                                                                                                                                                                                                             Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Papionini | Macaca
#> 48                                                                                                                                                                                                                                                                             Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Papionini | Macaca
#> 49                                                                                                                                                                                                                                                                             Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Papionini | Macaca
#> 50                                                                                                                                                                                                                                                                             Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Papionini | Macaca
#> 51                                                                                                                                                                                                                                                                             Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Papionini | Macaca
#> 52                                                                                                                                                                                                                                                                             Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Papionini | Macaca
#> 53                                                                                                                                                                                                                                                                             Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Papionini | Macaca
#> 54                                                                                                                                                                                                                                                                             Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Papionini | Macaca
#> 55                                                                                                                                                                                                                                                                             Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Papionini | Macaca
#> 56                                                                                                                                                                                                                                                                             Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Papionini | Macaca
#> 57                                                                                                                                                                                                                                                              Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Papionini | Papio | Papio ursinus
#> 58                                                                                                                                                                                                                                                              Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Papionini | Papio | Papio ursinus
#> 59                                                                                                                                                                                                                                         Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Cercopithecini | Chlorocebus | Chlorocebus pygerythrus
#> 60                                                                                                                                                                                                                                                                                                                                                                                                                                  Animalia | Chordata | Mammalia | Primates | Cercopithecidae | Macaca | Macaca sinica
#> 61                                                                                                                                                                                                                                            Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Cercopithecini | Cercopithecus | Cercopithecus mona
#> 62                                                                                                                                                                                                                                            Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Cercopithecini | Cercopithecus | Cercopithecus mona
#> 63                                                                                                                                                                                                                                                                                                              Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Pan
#> 64                                                                                                                                                                                                                                                                                                              Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Pan
#> 65                                                                                                                                                                                                                                                                                                              Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Pan
#> 66                                                                                                                                                                                                                                                                                                              Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Pan
#> 67                                                                                                   Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Strepsirrhini | Lorisiformes | Galagidae | Galagoides | Galagoides demidoff
#> 68                                             Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Haplorrhini | Anthropoidea | Catarrhini | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Papionini | Papio | Papio anubis
#> 69                              Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Haplorrhini | Anthropoidea | Catarrhini | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Papionini | Mandrillus | Mandrillus leucophaeus
#> 70                                                                            Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Haplorrhini | Anthropoidea | Catarrhini | Hominoidea | Hominidae | Ponginae | Pongo | Pongo abelii
#> 71                                                                            Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Haplorrhini | Anthropoidea | Catarrhini | Hominoidea | Hominidae | Ponginae | Pongo | Pongo abelii
#> 72                                               Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Haplorrhini | Anthropoidea | Catarrhini | Cercopithecoidea | Cercopithecidae | Colobinae | Colobini | Colobus | Colobus guereza
#> 73                                Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Haplorrhini | Anthropoidea | Catarrhini | Cercopithecoidea | Cercopithecidae | Colobinae | Presbytini | Semnopithecus | Semnopithecus entellus
#> 74                     Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Haplorrhini | Anthropoidea | Catarrhini | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Cercopithecini | Cercopithecus | Cercopithecus nictitans
#> 75                                                                                     Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Haplorrhini | Anthropoidea | Platyrrhini | Callitrichidae | Saguinus | Saguinus imperator
#> 76                                                                                     Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Haplorrhini | Anthropoidea | Platyrrhini | Callitrichidae | Saguinus | Saguinus imperator
#> 77                                                                                     Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Haplorrhini | Anthropoidea | Platyrrhini | Callitrichidae | Saguinus | Saguinus imperator
#> 78                                                                                     Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Haplorrhini | Anthropoidea | Platyrrhini | Callitrichidae | Saguinus | Saguinus imperator
#> 79                      Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Haplorrhini | Anthropoidea | Catarrhini | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Cercopithecini | Cercopithecus | Cercopithecus pogonias
#> 80                     Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Haplorrhini | Anthropoidea | Catarrhini | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Cercopithecini | Cercopithecus | Cercopithecus neglectus
#> 81                                                                             Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Strepsirrhini | Lemuriformes | Cheirogaleoidea | Cheirogaleidae | Microcebus | Microcebus murinus
#> 82                                                                             Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Strepsirrhini | Lemuriformes | Cheirogaleoidea | Cheirogaleidae | Microcebus | Microcebus murinus
#> 83                                                                             Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Strepsirrhini | Lemuriformes | Cheirogaleoidea | Cheirogaleidae | Microcebus | Microcebus murinus
#> 84                                                                                                           Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Strepsirrhini | Lemuriformes | Lemuridae | Eulemur | Eulemur fulvus
#> 85                                                                                                           Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Strepsirrhini | Lemuriformes | Lemuridae | Eulemur | Eulemur fulvus
#> 86                                                                                                  Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Haplorrhini | Anthropoidea | Catarrhini | Cercopithecoidea | Cercopithecidae
#> 87                                                                                                  Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Haplorrhini | Anthropoidea | Catarrhini | Cercopithecoidea | Cercopithecidae
#> 88                                                                                                  Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Haplorrhini | Anthropoidea | Catarrhini | Cercopithecoidea | Cercopithecidae
#> 89                                                                                                  Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Haplorrhini | Anthropoidea | Catarrhini | Cercopithecoidea | Cercopithecidae
#> 90                                                                                                  Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Haplorrhini | Anthropoidea | Catarrhini | Cercopithecoidea | Cercopithecidae
#> 91                                                                                                  Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Haplorrhini | Anthropoidea | Catarrhini | Cercopithecoidea | Cercopithecidae
#> 92                                                                                                  Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Haplorrhini | Anthropoidea | Catarrhini | Cercopithecoidea | Cercopithecidae
#> 93                                                                                                  Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Haplorrhini | Anthropoidea | Catarrhini | Cercopithecoidea | Cercopithecidae
#> 94                                                                                                  Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Haplorrhini | Anthropoidea | Catarrhini | Cercopithecoidea | Cercopithecidae
#> 95                                                                                                  Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Haplorrhini | Anthropoidea | Catarrhini | Cercopithecoidea | Cercopithecidae
#> 96                                                                                                  Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Haplorrhini | Anthropoidea | Catarrhini | Cercopithecoidea | Cercopithecidae
#> 97                                                                                                  Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Strepsirrhini | Lemuriformes | Cheirogaleoidea | Cheirogaleidae | Microcebus
#> 98                                                                                                                                                                                                                                                                                                             Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 99                                                                                                                                                                                                                                                                                                             Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 100                                                                                                                                                                                                                                                                                                            Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 101                                                                                                                                                                                                                                                                                                            Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 102                                                                                                                                                                                                                                                                                                            Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 103                                                                                                                                                                                                                                                                                                            Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 104                                                                                                                                                                                                                                                                                                            Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 105                                                                                                                                                                                                                                                                                                            Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 106                                                                                                                                      root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Strepsirrhini | Lemuriformes | Cheirogaleidae
#> 107                                                                                            root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Cercopithecoidea | Cercopithecidae | Colobinae
#> 108                                                                                            root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Cercopithecoidea | Cercopithecidae | Colobinae
#> 109                                                                                                                                                                                                                                                                          Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Colobinae | Presbytini | Rhinopithecus
#> 110                                                                                                                                                                                                                                                                          Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Colobinae | Presbytini | Rhinopithecus
#> 111                                                                                                                                                                                                                                                                          Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Colobinae | Presbytini | Rhinopithecus
#> 112                                                                                                                                                                                                                                                                          Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Colobinae | Presbytini | Rhinopithecus
#> 113                                                                                                                                                                                                                                                                          Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Colobinae | Presbytini | Rhinopithecus
#> 114                                                                                                                                                                                                                                                                          Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Colobinae | Presbytini | Rhinopithecus
#> 115                                                                                                                                                                                                                                                                          Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Colobinae | Presbytini | Rhinopithecus
#> 116                                                                                                                                                                                                                                                                          Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Colobinae | Presbytini | Rhinopithecus
#> 117                                                                                                                                                                                                                                                                          Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Colobinae | Presbytini | Rhinopithecus
#> 118                                                                                                                                                                                                                                                                          Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Colobinae | Presbytini | Rhinopithecus
#> 119                                                                                                                                                                                                                                                                          Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Colobinae | Presbytini | Rhinopithecus
#> 120                                                                                                                                                                                                                                                                          Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Colobinae | Presbytini | Rhinopithecus
#> 121                                                                                                                                                                                                                                                                          Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Colobinae | Presbytini | Rhinopithecus
#> 122                                                                                                                                                                                                                                                                          Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Colobinae | Presbytini | Rhinopithecus
#> 123                                                                                                                                                                                                                                                                          Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Colobinae | Presbytini | Rhinopithecus
#> 124                                                                                                                                                                                                                                                                          Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Colobinae | Presbytini | Rhinopithecus
#> 125                                                                                                                                                                                                                                                                                                                                                                                         Boreoeutheria | Euarchontoglires | Euarchonta | Primatomorpha | Primates | Haplorhini | Simiiformes | Platyrrhini | Atelidae
#> 126                                                                                                                                                                                                                                                                                                                                                                                         Boreoeutheria | Euarchontoglires | Euarchonta | Primatomorpha | Primates | Haplorhini | Simiiformes | Platyrrhini | Atelidae
#> 127                                                                                                                                                                                                                                                                                                                                                                                         Boreoeutheria | Euarchontoglires | Euarchonta | Primatomorpha | Primates | Haplorhini | Simiiformes | Platyrrhini | Atelidae
#> 128                                                                                                                                                                                                                                                                                                                                                                                         Boreoeutheria | Euarchontoglires | Euarchonta | Primatomorpha | Primates | Haplorhini | Simiiformes | Platyrrhini | Atelidae
#> 129                                                                                                                                  root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Platyrrhini | Cebidae
#> 130                                                                                                                                  root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Platyrrhini | Cebidae
#> 131                                                                                                                                  root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Platyrrhini | Cebidae
#> 132                                                                                                                                  root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Platyrrhini | Cebidae
#> 133                                                                                                                                  root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Platyrrhini | Cebidae
#> 134                                                                                                                                  root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Platyrrhini | Cebidae
#> 135                                                                                                                                root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Hominoidea
#> 136                                                                                                                                                                                                                                                                             Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Colobinae | Colobini | Piliocolobus
#> 137                                                                                                 root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Hominoidea | Hominidae | Ponginae | Pongo
#> 138                                                                                                 root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Hominoidea | Hominidae | Ponginae | Pongo
#> 139                                                                                                 root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Hominoidea | Hominidae | Ponginae | Pongo
#> 140                                                                                        root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Platyrrhini | Atelidae | Alouattinae | Alouatta | Alouatta sara
#> 141                                                                        root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Chlorocebus
#> 142                                                                        root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Chlorocebus
#> 143                                                                        root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Chlorocebus
#> 144                                                                        root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Chlorocebus
#> 145                                                                        root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Chlorocebus
#> 146                                                                        root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Chlorocebus
#> 147                                                                        root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Chlorocebus
#> 148                                                                        root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Chlorocebus
#> 149                                                                        root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Chlorocebus
#> 150                                                                                                                                           root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Strepsirrhini | Lemuriformes | Lemuridae
#> 151                                                                                                                                           root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Strepsirrhini | Lemuriformes | Lemuridae
#> 152                                                                                                                                           root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Strepsirrhini | Lemuriformes | Lemuridae
#> 153                                                                                                                                           root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Strepsirrhini | Lemuriformes | Lemuridae
#> 154                                                                                                                                           root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Strepsirrhini | Lemuriformes | Lemuridae
#> 155                                                                                                                                           root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Strepsirrhini | Lemuriformes | Lemuridae
#> 156                                                                                                                                           root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Strepsirrhini | Lemuriformes | Lemuridae
#> 157                                                                                                                                           root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Strepsirrhini | Lemuriformes | Lemuridae
#> 158                                                                                                                                           root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Strepsirrhini | Lemuriformes | Lemuridae
#> 159                                                                                                                                           root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Strepsirrhini | Lemuriformes | Lemuridae
#> 160                                                                          root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Platyrrhini | Atelidae | Atelinae | Ateles | unclassified Ateles | Ateles sp.
#> 161                                                                                                                                                                                                                                                                                                                             Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Atelidae | Protopithecus
#> 162                                                                                                       root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Strepsirrhini | Lemuriformes | Indriidae | Propithecus | Propithecus diadema
#> 163                                                                                                                               root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Strepsirrhini | Lemuriformes | Lemuridae | Hapalemur
#> 164                                                                                                     root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Strepsirrhini | Lemuriformes | Indriidae | Propithecus | Propithecus coquereli
#> 165                                                                                                     root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Strepsirrhini | Lemuriformes | Indriidae | Propithecus | Propithecus coquereli
#> 166                                                         root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Cercopithecoidea | Cercopithecidae | Colobinae | Presbytis | Presbytis melalophos
#> 167                                                  root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Hominoidea | Hominidae | Homininae | Gorilla | Gorilla gorilla | Gorilla gorilla gorilla
#> 168                                                  root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Hominoidea | Hominidae | Homininae | Gorilla | Gorilla gorilla | Gorilla gorilla gorilla
#> 169                                                                                                        root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Platyrrhini | Atelidae | Atelinae | Brachyteles
#> 170                                                                                                        root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Platyrrhini | Atelidae | Atelinae | Brachyteles
#> 171                                                                                                        root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Platyrrhini | Atelidae | Atelinae | Brachyteles
#> 172                                                                                         root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Platyrrhini | Atelidae | Atelinae | Lagothrix | Lagothrix cana
#> 173                                                       Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Euarchontoglires | Euarchonta | Primates | Haplorrhini | Anthropoidea | Catarrhini | Cercopithecoidea | Cercopithecidae | Colobinae | Presbytini | Trachypithecus
#> 174                                                root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Hominoidea | Hominidae | Homininae | Gorilla | Gorilla beringei | Gorilla beringei graueri
#> 175                                                root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Hominoidea | Hominidae | Homininae | Gorilla | Gorilla beringei | Gorilla beringei graueri
#> 176                                                            root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Macaca | Macaca munzala
#> 177                                                            root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Macaca | Macaca munzala
#> 178                                                                                                                root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Tarsiiformes | Tarsiidae | Carlito | Carlito syrichta
#> 179                                                                                                                                           root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Strepsirrhini | Lorisiformes | Galagidae
#> 180                                                                                                                                 root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Strepsirrhini | Lemuriformes | Lemuridae | Eulemur
#> 181 root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Cercopithecus | Cercopithecus albogularis | Cercopithecus albogularis erythrarchus
#> 182 root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Cercopithecus | Cercopithecus albogularis | Cercopithecus albogularis erythrarchus
#> 183                                                                              root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Platyrrhini | Atelidae | Atelinae | Brachyteles | Brachyteles arachnoides
#> 184                                            root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Chlorocebus | Chlorocebus djamdjamensis
#> 185                                                                                                              root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Strepsirrhini | Lemuriformes | Indriidae | Avahi | Avahi occidentalis
#> 186                                                root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Cercopithecus | Cercopithecus dryas
#> 187                                                 root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Cercopithecoidea | Cercopithecidae | Colobinae | Trachypithecus | Trachypithecus obscurus
#> 188                                                                                                              root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Platyrrhini | Cebidae | Cebinae | Sapajus
#> 189                                                                                                                                                                                                                                                                              Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Colobinae | Presbytini | Pygathrix
#> 190                                                                                                                                                                                                                                                         Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Colobinae | Presbytini | Pygathrix | Pygathrix nigripes
#> 191                                                                                                                                                                                                                                                                                     Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Strepsirrhini | Chiromyiformes | Daubentoniidae | Daubentonia | Daubentonia madagascariensis
#> 192                                                                                                                                                                                                  Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Cercopithecini | Chlorocebus | Chlorocebus pygerythrus | Chlorocebus pygerythrus rufoviridis
#> 193                                                                                                                                                                                                  Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Cercopithecini | Chlorocebus | Chlorocebus pygerythrus | Chlorocebus pygerythrus pygerythrus
#> 194                                                                                                                                                                                                         Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Cercopithecini | Cercopithecus | Cercopithecus cephus | Cercopithecus cephus cephodes
#> 195                                                                                                                                                                                               Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Cercopithecini | Cercopithecus | Cercopithecus erythrotis | Cercopithecus erythrotis erythrotis
#> 196                                                                                                                                                                                                           Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Cercopithecini | Cercopithecus | Cercopithecus cephus | Cercopithecus cephus cephus
#> 197                                                                                                                                                                                                                                   Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Papionini | Papio | Papio ursinus | Papio ursinus griseipes
#> 198                                                                                                                                                                                                                                                                                Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Cercopithecini
#> 199                                                                                                                                                                                                         Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Cercopithecini | Cercopithecus | Cercopithecus mitis | Cercopithecus mitis stuhlmanni
#> 200                                                                                                                                                                                                        Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Cercopithecini | Allochrocebus | Allochrocebus preussi | Allochrocebus preussi preussi
#> 201                                          root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Cercopithecus | Cercopithecus albogularis
#> 202                                          root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Cercopithecoidea | Cercopithecidae | Cercopithecinae | Cercopithecus | Cercopithecus albogularis
#> 203                                                                                                                                                                                                                                                                                       Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Strepsirrhini | Lemuriformes | Lemuroidea | Lemuridae | Hapalemur | Hapalemur meridionalis
#> 204                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 <NA>
#>     source_specimen_life_stage interaction_type
#> 1                           NA     preyedUponBy
#> 2                           NA     preyedUponBy
#> 3                           NA     preyedUponBy
#> 4                           NA     preyedUponBy
#> 5                           NA     preyedUponBy
#> 6                           NA     preyedUponBy
#> 7                           NA     preyedUponBy
#> 8                           NA     preyedUponBy
#> 9                           NA     preyedUponBy
#> 10                          NA     preyedUponBy
#> 11                          NA     preyedUponBy
#> 12                          NA     preyedUponBy
#> 13                          NA     preyedUponBy
#> 14                          NA     preyedUponBy
#> 15                          NA     preyedUponBy
#> 16                          NA     preyedUponBy
#> 17                          NA     preyedUponBy
#> 18                          NA     preyedUponBy
#> 19                          NA     preyedUponBy
#> 20                          NA     preyedUponBy
#> 21                          NA     preyedUponBy
#> 22                          NA     preyedUponBy
#> 23                          NA     preyedUponBy
#> 24                          NA     preyedUponBy
#> 25                          NA     preyedUponBy
#> 26                          NA     preyedUponBy
#> 27                          NA     preyedUponBy
#> 28                          NA     preyedUponBy
#> 29                          NA     preyedUponBy
#> 30                          NA     preyedUponBy
#> 31                          NA     preyedUponBy
#> 32                          NA     preyedUponBy
#> 33                          NA     preyedUponBy
#> 34                          NA     preyedUponBy
#> 35                          NA     preyedUponBy
#> 36                          NA     preyedUponBy
#> 37                          NA     preyedUponBy
#> 38                          NA     preyedUponBy
#> 39                          NA     preyedUponBy
#> 40                          NA     preyedUponBy
#> 41                          NA     preyedUponBy
#> 42                          NA     preyedUponBy
#> 43                          NA     preyedUponBy
#> 44                          NA     preyedUponBy
#> 45                          NA     preyedUponBy
#> 46                          NA     preyedUponBy
#> 47                          NA     preyedUponBy
#> 48                          NA     preyedUponBy
#> 49                          NA     preyedUponBy
#> 50                          NA     preyedUponBy
#> 51                          NA     preyedUponBy
#> 52                          NA     preyedUponBy
#> 53                          NA     preyedUponBy
#> 54                          NA     preyedUponBy
#> 55                          NA     preyedUponBy
#> 56                          NA     preyedUponBy
#> 57                          NA     preyedUponBy
#> 58                          NA     preyedUponBy
#> 59                          NA     preyedUponBy
#> 60                          NA     preyedUponBy
#> 61                          NA     preyedUponBy
#> 62                          NA     preyedUponBy
#> 63                          NA     preyedUponBy
#> 64                          NA     preyedUponBy
#> 65                          NA     preyedUponBy
#> 66                          NA     preyedUponBy
#> 67                          NA     preyedUponBy
#> 68                          NA     preyedUponBy
#> 69                          NA     preyedUponBy
#> 70                          NA     preyedUponBy
#> 71                          NA     preyedUponBy
#> 72                          NA     preyedUponBy
#> 73                          NA     preyedUponBy
#> 74                          NA     preyedUponBy
#> 75                          NA     preyedUponBy
#> 76                          NA     preyedUponBy
#> 77                          NA     preyedUponBy
#> 78                          NA     preyedUponBy
#> 79                          NA     preyedUponBy
#> 80                          NA     preyedUponBy
#> 81                          NA     preyedUponBy
#> 82                          NA     preyedUponBy
#> 83                          NA     preyedUponBy
#> 84                          NA     preyedUponBy
#> 85                          NA     preyedUponBy
#> 86                          NA     preyedUponBy
#> 87                          NA     preyedUponBy
#> 88                          NA     preyedUponBy
#> 89                          NA     preyedUponBy
#> 90                          NA     preyedUponBy
#> 91                          NA     preyedUponBy
#> 92                          NA     preyedUponBy
#> 93                          NA     preyedUponBy
#> 94                          NA     preyedUponBy
#> 95                          NA     preyedUponBy
#> 96                          NA     preyedUponBy
#> 97                          NA     preyedUponBy
#> 98                          NA     preyedUponBy
#> 99                          NA     preyedUponBy
#> 100                         NA     preyedUponBy
#> 101                         NA     preyedUponBy
#> 102                         NA     preyedUponBy
#> 103                         NA     preyedUponBy
#> 104                         NA     preyedUponBy
#> 105                         NA     preyedUponBy
#> 106                         NA     preyedUponBy
#> 107                         NA     preyedUponBy
#> 108                         NA     preyedUponBy
#> 109                         NA     preyedUponBy
#> 110                         NA     preyedUponBy
#> 111                         NA     preyedUponBy
#> 112                         NA     preyedUponBy
#> 113                         NA     preyedUponBy
#> 114                         NA     preyedUponBy
#> 115                         NA     preyedUponBy
#> 116                         NA     preyedUponBy
#> 117                         NA     preyedUponBy
#> 118                         NA     preyedUponBy
#> 119                         NA     preyedUponBy
#> 120                         NA     preyedUponBy
#> 121                         NA     preyedUponBy
#> 122                         NA     preyedUponBy
#> 123                         NA     preyedUponBy
#> 124                         NA     preyedUponBy
#> 125                         NA     preyedUponBy
#> 126                         NA     preyedUponBy
#> 127                         NA     preyedUponBy
#> 128                         NA     preyedUponBy
#> 129                         NA     preyedUponBy
#> 130                         NA     preyedUponBy
#> 131                         NA     preyedUponBy
#> 132                         NA     preyedUponBy
#> 133                         NA     preyedUponBy
#> 134                         NA     preyedUponBy
#> 135                         NA     preyedUponBy
#> 136                         NA     preyedUponBy
#> 137                         NA     preyedUponBy
#> 138                         NA     preyedUponBy
#> 139                         NA     preyedUponBy
#> 140                         NA     preyedUponBy
#> 141                         NA     preyedUponBy
#> 142                         NA     preyedUponBy
#> 143                         NA     preyedUponBy
#> 144                         NA     preyedUponBy
#> 145                         NA     preyedUponBy
#> 146                         NA     preyedUponBy
#> 147                         NA     preyedUponBy
#> 148                         NA     preyedUponBy
#> 149                         NA     preyedUponBy
#> 150                         NA     preyedUponBy
#> 151                         NA     preyedUponBy
#> 152                         NA     preyedUponBy
#> 153                         NA     preyedUponBy
#> 154                         NA     preyedUponBy
#> 155                         NA     preyedUponBy
#> 156                         NA     preyedUponBy
#> 157                         NA     preyedUponBy
#> 158                         NA     preyedUponBy
#> 159                         NA     preyedUponBy
#> 160                         NA     preyedUponBy
#> 161                         NA     preyedUponBy
#> 162                         NA     preyedUponBy
#> 163                         NA     preyedUponBy
#> 164                         NA     preyedUponBy
#> 165                         NA     preyedUponBy
#> 166                         NA     preyedUponBy
#> 167                         NA     preyedUponBy
#> 168                         NA     preyedUponBy
#> 169                         NA     preyedUponBy
#> 170                         NA     preyedUponBy
#> 171                         NA     preyedUponBy
#> 172                         NA     preyedUponBy
#> 173                         NA     preyedUponBy
#> 174                         NA     preyedUponBy
#> 175                         NA     preyedUponBy
#> 176                         NA     preyedUponBy
#> 177                         NA     preyedUponBy
#> 178                         NA     preyedUponBy
#> 179                         NA     preyedUponBy
#> 180                         NA     preyedUponBy
#> 181                         NA     preyedUponBy
#> 182                         NA     preyedUponBy
#> 183                         NA     preyedUponBy
#> 184                         NA     preyedUponBy
#> 185                         NA     preyedUponBy
#> 186                         NA     preyedUponBy
#> 187                         NA     preyedUponBy
#> 188                         NA     preyedUponBy
#> 189                         NA     preyedUponBy
#> 190                         NA     preyedUponBy
#> 191                         NA     preyedUponBy
#> 192                         NA     preyedUponBy
#> 193                         NA     preyedUponBy
#> 194                         NA     preyedUponBy
#> 195                         NA     preyedUponBy
#> 196                         NA     preyedUponBy
#> 197                         NA     preyedUponBy
#> 198                         NA     preyedUponBy
#> 199                         NA     preyedUponBy
#> 200                         NA     preyedUponBy
#> 201                         NA     preyedUponBy
#> 202                         NA     preyedUponBy
#> 203                         NA     preyedUponBy
#> 204                         NA             <NA>
#>                                                                                         target_taxon_external_id
#> 1                                                                                                      COL:5K5LY
#> 2                                                                                                     WD:Q729553
#> 3                                                                                                      COL:4CGXR
#> 4                                                                                                      COL:7KGW9
#> 5                                                                                                    NCBI:508772
#> 6                                                                                                       COL:F4NM
#> 7                                                                                                      COL:456G4
#> 8                                                                                                      COL:4QY48
#> 9                                                                                                      COL:47WH7
#> 10                                                                                                     COL:3F3KT
#> 11                                                                                                     COL:5TZZX
#> 12                                                                                                     COL:5Z3MZ
#> 13                                                                                                    EOL:740700
#> 14                                                                                                     COL:5YS8S
#> 15                                                                                                     COL:64W86
#> 16                                                                                                    EOL:810644
#> 17                                                                                                    EOL:740720
#> 18                                                                                                     COL:3VB49
#> 19                                                                                                    EOL:764100
#> 20                                                                                                     COL:PB2GF
#> 21                                                                                                    EOL:759381
#> 22                                                                                                     COL:6ZX7S
#> 23                                                                                                     COL:BXWKF
#> 24                                                                                                     COL:3QGJR
#> 25                                                                                                     COL:34WNR
#> 26                                                                                                     COL:53PPR
#> 27                                                                                                     COL:6584C
#> 28                                                                                                  NCBI:1496311
#> 29                                                                                                     COL:3XMDC
#> 30                                                                                                     COL:46H7Y
#> 31                                                                                                     NCBI:8493
#> 32                                                                                                      COL:MNYK
#> 33                                                                                                  GBIF:8054654
#> 34                                                                                                     COL:636X2
#> 35                                                                                                     COL:6MB3T
#> 36                                                                                                     COL:6MB3T
#> 37                                                                                                     COL:4QHKG
#> 38                                                                                                     COL:3XMDC
#> 39                                                                                                     COL:636X2
#> 40                                                                                                   NCBI:202280
#> 41                                                                                                     COL:636X2
#> 42                                                                                                    NCBI:74535
#> 43                                                                                                    NCBI:95911
#> 44                                                                                                    NCBI:61393
#> 45                                                                                                     NCBI:9663
#> 46                                                                                                     NCBI:9635
#> 47                                                                                                     NCBI:9682
#> 48                                                                                                     NCBI:9639
#> 49                                                                                                    NCBI:61409
#> 50                                                                                                    NCBI:37028
#> 51                                                                                                  NCBI:1496304
#> 52                                                                                                    NCBI:61451
#> 53                                                                                                     NCBI:9611
#> 54                                                                                                     EOL:14134
#> 55                                                                                                     NCBI:9694
#> 56                                                                                                     NCBI:9681
#> 57                                                                                                     COL:5K5LY
#> 58                                                                                                     COL:5DXLW
#> 59                                                                                                     COL:4QY4Q
#> 60                                                                                                      COL:ZKNN
#> 61                                                                                                     COL:6MB3T
#> 62                                                                                                     COL:4QY54
#> 63                                                                                                     EOL:14134
#> 64                                                                                                     COL:636X2
#> 65                                                                                                    NCBI:30972
#> 66                                                                                                     NCBI:9691
#> 67                                                                                                     COL:7925W
#> 68                                                                                                    EOL:328673
#> 69                                                                                                     NCBI:6752
#> 70                                                                                                     NCBI:9694
#> 71                                                                                                    NCBI:30972
#> 72                                                                                                    NCBI:37010
#> 73                                                                                                      COL:ZKNN
#> 74                                                                                                     COL:6MB3T
#> 75                                                                                                     COL:62QPG
#> 76                                                                                                     NCBI:9681
#> 77                                                                                                     NCBI:8570
#> 78                                                                                                    NCBI:32538
#> 79                                                                                                     COL:6MB3T
#> 80                                                                                                     COL:6MB3T
#> 81                                                                                                    NCBI:47180
#> 82                                                                                                     NCBI:8570
#> 83                                                                                                    NCBI:30458
#> 84                                                                                                     COL:636X2
#> 85                                                                                                    EOL:795590
#> 86                                                                                                     NCBI:9632
#> 87                                                                                                      COL:ZKNK
#> 88                                                                                                     NCBI:9655
#> 89                                                                                                     NCBI:9676
#> 90                                                                                                    NCBI:33415
#> 91                                                                                                    NCBI:34984
#> 92                                                                                                     NCBI:8493
#> 93                                                                                                    NCBI:56259
#> 94                                                                                                      EOL:7676
#> 95                                                                                                     NCBI:9681
#> 96                                                                                                     NCBI:9604
#> 97                                                                                                    NCBI:83691
#> 98                                                                                                      NCBI:662
#> 99                                                                                                    EOL:452958
#> 100                                                                                                    NCBI:8493
#> 101                                                                                                    NCBI:9691
#> 102                                                                                                    NCBI:9681
#> 103                                                                                                    EOL:14134
#> 104                                                                                                    NCBI:9694
#> 105                                                                                                   NCBI:33554
#> 106                                                                                                   NCBI:30615
#> 107                                                                                                    NCBI:9694
#> 108                                                                                                    NCBI:9691
#> 109                                                                                                    EOL:14134
#> 110                                                                                                   NCBI:30396
#> 111                                                                                                  NCBI:554455
#> 112                                                                                                   EOL:328688
#> 113                                                                                                    NCBI:8960
#> 114                                                                                                    NCBI:9642
#> 115                                                                                                    NCBI:8956
#> 116                                                                                                   WD:Q200848
#> 117                                                                                                    EOL:19888
#> 118                                                                                                   NCBI:43517
#> 119                                                                                                    NCBI:8957
#> 120                                                                                                    NCBI:9611
#> 121                                                                                                   NCBI:29064
#> 122                                                                                                    NCBI:8962
#> 123                                                                                                    NCBI:9639
#> 124                                                                                                    COL:636X2
#> 125                                                                                                    NCBI:9604
#> 126                                                                                                   NCBI:56259
#> 127                                                                                                    NCBI:9681
#> 128                                                                                                     EOL:7676
#> 129                                                                                                    NCBI:9681
#> 130                                                                                                     EOL:7676
#> 131                                                                                                   NCBI:56259
#> 132                                                                                                    NCBI:9604
#> 133                                                                                                    COL:622QH
#> 134                                                                                                    NCBI:9655
#> 135                                                                                                    COL:636X2
#> 136                                                                                                     COL:6D2G
#> 137                                                                                                    COL:636X2
#> 138                                                                                                    NCBI:9681
#> 139                                                                                                    EOL:14134
#> 140                                                                                                    COL:636X2
#> 141                                                                                                    EOL:14134
#> 142 https://www.mammaldiversity.org/explore.html#genus=Canis&species=familiaris&id=1005940&subspecies=familiaris
#> 143                                                                                                    COL:4QY4Q
#> 144                                                                                                   NCBI:30396
#> 145                                                                                                   NCBI:56259
#> 146                                                                                                    NCBI:8570
#> 147                                                                                                    NCBI:9691
#> 148                                                                                                    COL:636X2
#> 149                                                                                                     COL:6D2G
#> 150                                                                                                    NCBI:9604
#> 151                                                                                                    NCBI:8570
#> 152                                                                                                    NCBI:9685
#> 153                                                                                                    COL:636X2
#> 154                                                                                                     EOL:7676
#> 155                                                                                                    NCBI:9681
#> 156                                                                                                    NCBI:9611
#> 157                                                                                                    NCBI:9615
#> 158                                                                                                   WD:Q641742
#> 159                                                                                                   NCBI:94188
#> 160                                                                                                    COL:636X2
#> 161                                                                                                    COL:636X2
#> 162                                                                                                    COL:636X2
#> 163                                                                                                    COL:636X2
#> 164                                                                                                    COL:636X2
#> 165                                                                                                   EOL:795590
#> 166                                                                                                    COL:3XMDC
#> 167                                                                                                    COL:636X2
#> 168                                                                                                   NCBI:30972
#> 169                                                                                                    COL:4CGXQ
#> 170                                                                                                    EOL:14134
#> 171                                                                                                    COL:636X2
#> 172                                                                                                  NCBI:202280
#> 173                                                                                                    COL:636X2
#> 174                                                                                                    COL:636X2
#> 175                                                                                                  NCBI:165861
#> 176                                                                                                    NCBI:9606
#> 177                                                                                                    COL:636X2
#> 178                                                                                                    NCBI:9681
#> 179                                                                                                    NCBI:9604
#> 180                                                                                                    COL:636X2
#> 181                                                                                                  NCBI:252802
#> 182                                                                                                    NCBI:9691
#> 183                                                                                                    COL:636X2
#> 184                                                                                                    COL:636X2
#> 185                                                                                                    COL:636X2
#> 186                                                                                                    COL:636X2
#> 187                                                                                                    NCBI:9681
#> 188                                                                                                 WD:Q15138218
#> 189                                                                                                   NCBI:13036
#> 190                                                                                                  NCBI:165861
#> 191                                                                                                    COL:6MB3T
#> 192                                                                                                   NCBI:37010
#> 193                                                                                                   WD:Q591640
#> 194                                                                                                    COL:6MB3T
#> 195                                                                                                    COL:6MB3T
#> 196                                                                                                    COL:6MB3T
#> 197                                                                                                     COL:ZKNK
#> 198                                                                                                   WD:Q501733
#> 199                                                                                                    COL:6MB3T
#> 200                                                                                                    COL:6MB3T
#> 201                                                                                                    NCBI:9691
#> 202                                                                                                  NCBI:252802
#> 203                                                                                                   EOL:795589
#> 204                                                                                                         <NA>
#>                  target_taxon_name
#> 1           Panthera pardus pardus
#> 2            Panthera pardus fusca
#> 3                  Panthera pardus
#> 4        Panthera leo melanochaita
#> 5                 Myotis escalerai
#> 6               Antrozous pallidus
#> 7                Myotis mystacinus
#> 8                Python bivittatus
#> 9              Notolabrus fucicola
#> 10               Galeocerdo cuvier
#> 11            Amblyomma americanum
#> 12               Chrysops relictus
#> 13               Aedes triseriatus
#> 14             Chrysops caecutiens
#> 15                Aedes atlanticus
#> 16             Forcipomyia taiwana
#> 17                Aedes sierrensis
#> 18                 Lipoptena cervi
#> 19                Aedes albopictus
#> 20            Haemadipsa zeylanica
#> 21           Haematopota pluvialis
#> 22             Stomoxys calcitrans
#> 23                           Aedes
#> 24                Ixodes pacificus
#> 25          Dermacentor variabilis
#> 26             Symphoromyia limata
#> 27                 Aedes squamiger
#> 28        Malayopython reticulatus
#> 29        Malayopython reticulatus
#> 30                 Neofelis diardi
#> 31                    Crocodylidae
#> 32               Bothrops leucurus
#> 33           Dendroaspis polylepis
#> 34                            Homo
#> 35                    Homo sapiens
#> 36                    Homo sapiens
#> 37                   Puma concolor
#> 38        Malayopython reticulatus
#> 39                            Homo
#> 40                  Harpia harpyja
#> 41                            Homo
#> 42          Panthera tigris tigris
#> 43                          Hyaena
#> 44                         Caracal
#> 45                       Mellivora
#> 46                        Melursus
#> 47                           Felis
#> 48                           Ursus
#> 49                      Pardofelis
#> 50                    Prionailurus
#> 51                    Malayopython
#> 52                        Neofelis
#> 53                           Canis
#> 54                        Panthera
#> 55                 Panthera tigris
#> 56                         Felidae
#> 57          Panthera pardus pardus
#> 58     Crocodylus niloticus cowiei
#> 59               Python natalensis
#> 60            Crocodylus palustris
#> 61                    Homo sapiens
#> 62                    Python sebae
#> 63                        Panthera
#> 64                            Homo
#> 65                        Agonidae
#> 66                 Panthera pardus
#> 67                   Python regius
#> 68                 Panthera pardus
#> 69                       Brachyura
#> 70                 Panthera tigris
#> 71                        Agonidae
#> 72  Pan troglodytes schweinfurthii
#> 73            Crocodylus palustris
#> 74                    Homo sapiens
#> 75                            Eira
#> 76                         Felidae
#> 77                       Serpentes
#> 78              Leopardus pardalis
#> 79                    Homo sapiens
#> 80                    Homo sapiens
#> 81                 Mirza coquereli
#> 82                       Serpentes
#> 83                    Strigiformes
#> 84                            Homo
#> 85    Acrantophis madagascariensis
#> 86                         Ursidae
#> 87            Crocodylus niloticus
#> 88                      Mustelidae
#> 89                       Hyaenidae
#> 90                     Nymphalidae
#> 91                      Pythonidae
#> 92                    Crocodylidae
#> 93                    Accipitridae
#> 94                         Canidae
#> 95                         Felidae
#> 96                       Hominidae
#> 97                           Mirza
#> 98                          Vibrio
#> 99          Agkistrodon contortrix
#> 100                   Crocodylidae
#> 101                Panthera pardus
#> 102                        Felidae
#> 103                       Panthera
#> 104                Panthera tigris
#> 105                      Carnivora
#> 106                 Cheirogaleidae
#> 107                Panthera tigris
#> 108                Panthera pardus
#> 109                       Panthera
#> 110                          Buteo
#> 111            Canis lupus laniger
#> 112                   Cuon alpinus
#> 113                         Aquila
#> 114               Ursus thibetanus
#> 115                      Accipiter
#> 116      Panthera tigris amoyensis
#> 117                           Cuon
#> 118                         Milvus
#> 119             Accipiter gentilis
#> 120                          Canis
#> 121                 Panthera uncia
#> 122              Aquila chrysaetos
#> 123                          Ursus
#> 124                           Homo
#> 125                      Hominidae
#> 126                   Accipitridae
#> 127                        Felidae
#> 128                        Canidae
#> 129                        Felidae
#> 130                        Canidae
#> 131                   Accipitridae
#> 132                      Hominidae
#> 133                  Alligatoridae
#> 134                     Mustelidae
#> 135                           Homo
#> 136                            Pan
#> 137                           Homo
#> 138                        Felidae
#> 139                       Panthera
#> 140                           Homo
#> 141                       Panthera
#> 142    Canis familiaris familiaris
#> 143              Python natalensis
#> 144                          Buteo
#> 145                   Accipitridae
#> 146                      Serpentes
#> 147                Panthera pardus
#> 148                           Homo
#> 149                            Pan
#> 150                      Hominidae
#> 151                      Serpentes
#> 152                    Felis catus
#> 153                           Homo
#> 154                        Canidae
#> 155                        Felidae
#> 156                          Canis
#> 157         Canis lupus familiaris
#> 158                     Eupleridae
#> 159             Cryptoprocta ferox
#> 160                           Homo
#> 161                           Homo
#> 162                           Homo
#> 163                           Homo
#> 164                           Homo
#> 165   Acrantophis madagascariensis
#> 166       Malayopython reticulatus
#> 167                           Homo
#> 168                       Agonidae
#> 169                  Panthera onca
#> 170                       Panthera
#> 171                           Homo
#> 172                 Harpia harpyja
#> 173                           Homo
#> 174                           Homo
#> 175                Danaus eresimus
#> 176                   Homo sapiens
#> 177                           Homo
#> 178                        Felidae
#> 179                      Hominidae
#> 180                           Homo
#> 181        Stephanoaetus coronatus
#> 182                Panthera pardus
#> 183                           Homo
#> 184                           Homo
#> 185                           Homo
#> 186                           Homo
#> 187                        Felidae
#> 188                         Harpia
#> 189                         Danaus
#> 190                Danaus eresimus
#> 191                   Homo sapiens
#> 192 Pan troglodytes schweinfurthii
#> 193        Stephanoaetus coronatus
#> 194                   Homo sapiens
#> 195                   Homo sapiens
#> 196                   Homo sapiens
#> 197           Crocodylus niloticus
#> 198          Polemaetus bellicosus
#> 199                   Homo sapiens
#> 200                   Homo sapiens
#> 201                Panthera pardus
#> 202        Stephanoaetus coronatus
#> 203           Acrantophis dumerili
#> 204                           <NA>
#>                                                                                                                                                                                                                                                                                                                                                                                                                                                                 target_taxon_path
#> 1                                                                                                                                                                                                                                                   Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Carnivora | Feliformia | Felidae | Pantherinae | Panthera | Panthera pardus | Panthera pardus pardus
#> 2                                                                                                                                                                                                                                                     Boreoeutheria | Laurasiatheria | Scrotifera | Ferungulata | Ferae | Pan-Carnivora | Carnivoramorpha | Carnivoraformes | Carnivora | Feliformia | Felidae | Pantherinae | Panthera | Panthera pardus | Panthera pardus fusca
#> 3                                                                                                                                                                                                                                                                            Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Carnivora | Feliformia | Felidae | Pantherinae | Panthera | Panthera pardus
#> 4                                                                                                                                                                                                                                                   Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Carnivora | Feliformia | Felidae | Pantherinae | Panthera | Panthera leo | Panthera leo melanochaita
#> 5                                                                                root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Chiroptera | Microchiroptera | Vespertilionidae | Myotis | Myotis escalerai
#> 6                                                                                                                                                                                                                   Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Chiroptera | Yangochiroptera | Vespertilionoidea | Vespertilionidae | Vespertilioninae | Antrozoini | Antrozous | Antrozous pallidus
#> 7                                                                                                                                                                                                                                   Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Chiroptera | Yangochiroptera | Vespertilionoidea | Vespertilionidae | Myotinae | Myotis | Myotis | Myotis mystacinus
#> 8                                                                                                                                                                                                                                                                                            Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Reptilia | Squamata | Serpentes | Alethinophidia | Pythonidae | Python | Python bivittatus
#> 9                                                                                                                                                                                                                                                                                  Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Actinopterygii | Actinopteri | Teleostei | Perciformes | Labridae | Julidinae | Notolabrus | Notolabrus fucicola
#> 10                                                                                                                                                                                                                                                                   Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Chondrichthyes | Elasmobranchii | Neoselachii | Selachii | Galeomorphi | Carcharhiniformes | Galeocerdonidae | Galeocerdo | Galeocerdo cuvier
#> 11                                                                                                                                                                                                                                                                                                                                           Eukaryota | Animalia | Arthropoda | Chelicerata | Arachnida | Parasitiformes | Ixodida | Ixodidae | Amblyomma | Amblyomma americanum
#> 12                                                                                                                                                                                                                                                                                                                 Eukaryota | Animalia | Arthropoda | Hexapoda | Insecta | Diptera | Tabanidae | Chrysopsinae | Chrysopsini | Chrysops | Chrysops (Chrysops) | Chrysops relictus
#> 13                                                                                                                                                                                                                  Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Protostomia | Ecdysozoa | Arthropoda | Pancrustacea | Hexapoda | Insecta | Pterygota | Neoptera | Endopterygota | Diptera | Culicomorpha | Culicidae | Aedes | Aedes triseriatus
#> 14                                                                                                                                                                                                                                                                                                               Eukaryota | Animalia | Arthropoda | Hexapoda | Insecta | Diptera | Tabanidae | Chrysopsinae | Chrysopsini | Chrysops | Chrysops (Chrysops) | Chrysops caecutiens
#> 15                                                                                                                                                                                                                                                                                                                            Eukaryota | Animalia | Arthropoda | Hexapoda | Insecta | Diptera | Culicidae | Culicinae | Aedini | Aedes | Aedes (Ochlerotatus) | Aedes atlanticus
#> 16                                                                                                                                                                                                    Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Protostomia | Ecdysozoa | Arthropoda | Pancrustacea | Hexapoda | Insecta | Pterygota | Neoptera | Endopterygota | Diptera | Culicomorpha | Ceratopogonidae | Forcipomyia | Forcipomyia taiwana
#> 17                                                                                                                                                                                                                   Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Protostomia | Ecdysozoa | Arthropoda | Pancrustacea | Hexapoda | Insecta | Pterygota | Neoptera | Endopterygota | Diptera | Culicomorpha | Culicidae | Aedes | Aedes sierrensis
#> 18                                                                                                                                                                                                                                                                                                                                                 Eukaryota | Animalia | Arthropoda | Hexapoda | Insecta | Diptera | Hippoboscidae | Hippoboscinae | Lipoptena | Lipoptena cervi
#> 19                                                                                                                                                                                                                   Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Protostomia | Ecdysozoa | Arthropoda | Pancrustacea | Hexapoda | Insecta | Pterygota | Neoptera | Endopterygota | Diptera | Culicomorpha | Culicidae | Aedes | Aedes albopictus
#> 20                                                                                                                                                                                                                                                                                                                                                            Eukaryota | Animalia | Annelida | Clitellata | Arhynchobdellida | Haemadipsidae | Haemadipsa | Haemadipsa zeylanica
#> 21                                                                                                                                                                                           Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Protostomia | Ecdysozoa | Arthropoda | Pancrustacea | Hexapoda | Insecta | Pterygota | Neoptera | Endopterygota | Diptera | Brachycera | Tabanomorpha | Tabanidae | Haematopota | Haematopota pluvialis
#> 22                                                                                                                                                                                                                                                                                                                                           Eukaryota | Animalia | Arthropoda | Hexapoda | Insecta | Diptera | Muscidae | Muscinae | Stomoxyini | Stomoxys | Stomoxys calcitrans
#> 23                                                                                                                                                                                                                                                                                                                                                                      Eukaryota | Animalia | Arthropoda | Hexapoda | Insecta | Diptera | Culicidae | Culicinae | Aedini | Aedes
#> 24                                                                                                                                                                                                                                                                                                                                                  Eukaryota | Animalia | Arthropoda | Chelicerata | Arachnida | Parasitiformes | Ixodida | Ixodidae | Ixodes | Ixodes pacificus
#> 25                                                                                                                                                                                                                                                                                                                                       Eukaryota | Animalia | Arthropoda | Chelicerata | Arachnida | Parasitiformes | Ixodida | Ixodidae | Dermacentor | Dermacentor variabilis
#> 26                                                                                                                                                                                                                                                                                                                 Eukaryota | Animalia | Arthropoda | Hexapoda | Insecta | Diptera | Rhagionidae | Spaniinae | Symphoromyia | Symphoromyia (Paraphoromyia) | Symphoromyia limata
#> 27                                                                                                                                                                                                                                                                                                                             Eukaryota | Animalia | Arthropoda | Hexapoda | Insecta | Diptera | Culicidae | Culicinae | Aedini | Aedes | Aedes (Ochlerotatus) | Aedes squamiger
#> 28                                         root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Sauropsida | Sauria | Lepidosauria | Squamata | Bifurcata | Unidentata | Episquamata | Toxicofera | Serpentes | Henophidia | Pythonidae | Malayopython | Malayopython reticulatus
#> 29                                                                                                                                                                                                                                                                              Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Reptilia | Squamata | Serpentes | Alethinophidia | Pythonidae | Malayopython | Malayopython reticulatus
#> 30                                                                                                                                                                                                                                                                           Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Carnivora | Feliformia | Felidae | Pantherinae | Neofelis | Neofelis diardi
#> 31                                                                                                                              root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Sauropsida | Sauria | Archelosauria | Archosauria | Crocodylia | Longirostres | Crocodylidae
#> 32                                                                                                                                                                                                                                                                             Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Reptilia | Squamata | Serpentes | Alethinophidia | Viperidae | Crotalinae | Bothrops | Bothrops leucurus
#> 33                                                                                                                                                                                                                                                                                                                                                                                                Animalia | Chordata | Squamata | Elapidae | Dendroaspis | Dendroaspis polylepis
#> 34                                                                                                                                                                                                                                                                      Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 35                                                                                                                                                                                                                                                       Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 36                                                                                                                                                                                                                                                       Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 37                                                                                                                                                                                                                                                                                     Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Carnivora | Feliformia | Felidae | Felinae | Puma | Puma concolor
#> 38                                                                                                                                                                                                                                                                              Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Reptilia | Squamata | Serpentes | Alethinophidia | Pythonidae | Malayopython | Malayopython reticulatus
#> 39                                                                                                                                                                                                                                                                      Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 40                     root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Sauropsida | Sauria | Archelosauria | Archosauria | Dinosauria | Saurischia | Theropoda | Coelurosauria | Aves | Neognathae | Accipitriformes | Accipitridae | Accipitrinae | Harpia | Harpia harpyja
#> 41                                                                                                                                                                                                                                                                      Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 42                                                      root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Feliformia | Felidae | Pantherinae | Panthera | Panthera tigris | Panthera tigris tigris
#> 43                                                                                                               root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Feliformia | Hyaenidae | Hyaena
#> 44                                                                                                      root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Feliformia | Felidae | Felinae | Caracal
#> 45                                                                                            root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Caniformia | Mustelidae | Mellivoriane | Mellivora
#> 46                                                                                                                                                                                                                                                                                                                                                                                                                                                                           <NA>
#> 47                                                                                                        root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Feliformia | Felidae | Felinae | Felis
#> 48                                                                                                                  root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Caniformia | Ursidae | Ursus
#> 49                                                                                                                                                                                                                                                                                                                                                                                                                                                                           <NA>
#> 50                                                                                                                                                                                                                                                                                                                                                                                                                                                                           <NA>
#> 51                                                                                                                                                                                                                                                                                                                                                                                                                                                                           <NA>
#> 52                                                                                                                                                                                                                                                                                                                                                                                                                                                                           <NA>
#> 53                                                                                                                  root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Caniformia | Canidae | Canis
#> 54                                                                                           Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Laurasiatheria | Scrotifera | Carnivora | Feliformia | Felidae | Pantherinae | Panthera
#> 55                                                                               root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Feliformia | Felidae | Pantherinae | Panthera | Panthera tigris
#> 56                                                                                                                          root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Feliformia | Felidae
#> 57                                                                                                                                                                                                                                                  Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Carnivora | Feliformia | Felidae | Pantherinae | Panthera | Panthera pardus | Panthera pardus pardus
#> 58                                                                                                                                                                                                                                                                               Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Reptilia | Crocodylia | Crocodylidae | Crocodylus | Crocodylus niloticus | Crocodylus niloticus cowiei
#> 59                                                                                                                                                                                                                                                                                           Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Reptilia | Squamata | Serpentes | Alethinophidia | Pythonidae | Python | Python natalensis
#> 60                                                                                                                                                                                                                                                                                                             Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Reptilia | Crocodylia | Crocodylidae | Crocodylus | Crocodylus palustris
#> 61                                                                                                                                                                                                                                                       Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 62                                                                                                                                                                                                                                                                                                Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Reptilia | Squamata | Serpentes | Alethinophidia | Pythonidae | Python | Python sebae
#> 63                                                                                           Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Laurasiatheria | Scrotifera | Carnivora | Feliformia | Felidae | Pantherinae | Panthera
#> 64                                                                                                                                                                                                                                                                      Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 65  root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Actinopterygii | Actinopteri | Neopterygii | Teleostei | Osteoglossocephalai | Clupeocephala | Euteleosteomorpha | Neoteleostei | Eurypterygia | Ctenosquamata | Acanthomorphata | Euacanthomorphacea | Percomorphaceae | Eupercaria | Perciformes | Cottioidei | Cottales | Agonidae
#> 66                                                                               root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Feliformia | Felidae | Pantherinae | Panthera | Panthera pardus
#> 67                                                                                                                                                                                                                                                                                               Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Reptilia | Squamata | Serpentes | Alethinophidia | Pythonidae | Python | Python regius
#> 68                                                                         Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Laurasiatheria | Scrotifera | Carnivora | Feliformia | Felidae | Pantherinae | Panthera | Panthera pardus
#> 69                                                                                                                                                                                        root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Protostomia | Ecdysozoa | Panarthropoda | Arthropoda | Mandibulata | Pancrustacea | Crustacea | Multicrustacea | Malacostraca | Eumalacostraca | Eucarida | Decapoda | Pleocyemata | Brachyura
#> 70                                                                               root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Feliformia | Felidae | Pantherinae | Panthera | Panthera tigris
#> 71  root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Actinopterygii | Actinopteri | Neopterygii | Teleostei | Osteoglossocephalai | Clupeocephala | Euteleosteomorpha | Neoteleostei | Eurypterygia | Ctenosquamata | Acanthomorphata | Euacanthomorphacea | Percomorphaceae | Eupercaria | Perciformes | Cottioidei | Cottales | Agonidae
#> 72         root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Hominoidea | Hominidae | Homininae | Pan | Pan troglodytes | Pan troglodytes schweinfurthii
#> 73                                                                                                                                                                                                                                                                                                             Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Reptilia | Crocodylia | Crocodylidae | Crocodylus | Crocodylus palustris
#> 74                                                                                                                                                                                                                                                       Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 75                                                                                                                                                                                                                                                                                                Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Carnivora | Caniformia | Mustelidae | Guloninae | Eira
#> 76                                                                                                                          root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Feliformia | Felidae
#> 77                                                                                                             root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Sauropsida | Sauria | Lepidosauria | Squamata | Bifurcata | Unidentata | Episquamata | Toxicofera | Serpentes
#> 78                                                                               root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Feliformia | Felidae | Felinae | Leopardus | Leopardus pardalis
#> 79                                                                                                                                                                                                                                                       Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 80                                                                                                                                                                                                                                                       Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 81                                                                      root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Strepsirrhini | Lemuriformes | Cheirogaleidae | Mirza | Mirza coquereli
#> 82                                                                                                             root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Sauropsida | Sauria | Lepidosauria | Squamata | Bifurcata | Unidentata | Episquamata | Toxicofera | Serpentes
#> 83                                                                                root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Sauropsida | Sauria | Archelosauria | Archosauria | Dinosauria | Saurischia | Theropoda | Coelurosauria | Aves | Neognathae | Strigiformes
#> 84                                                                                                                                                                                                                                                                      Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 85                                                                                                                            Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Reptilia | Diapsida | Lepidosauromorpha | Lepidosauria | Squamata | Serpentes | Alethinophidia | Sanziniidae | Acrantophis | Acrantophis madagascariensis
#> 86                                                                                                                          root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Caniformia | Ursidae
#> 87                                                                                                                                                                                                                                                                                                             Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Reptilia | Crocodylia | Crocodylidae | Crocodylus | Crocodylus niloticus
#> 88                                                                                                                       root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Caniformia | Mustelidae
#> 89                                                                                                                        root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Feliformia | Hyaenidae
#> 90                                                                                          root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Protostomia | Ecdysozoa | Panarthropoda | Arthropoda | Mandibulata | Pancrustacea | Hexapoda | Insecta | Dicondylia | Pterygota | Neoptera | Endopterygota | Amphiesmenoptera | Lepidoptera | Glossata | Neolepidoptera | Heteroneura | Ditrysia | Obtectomera | Papilionoidea | Nymphalidae
#> 91                                                                                   root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Sauropsida | Sauria | Lepidosauria | Squamata | Bifurcata | Unidentata | Episquamata | Toxicofera | Serpentes | Henophidia | Pythonidae
#> 92                                                                                                                              root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Sauropsida | Sauria | Archelosauria | Archosauria | Crocodylia | Longirostres | Crocodylidae
#> 93                                                              root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Sauropsida | Sauria | Archelosauria | Archosauria | Dinosauria | Saurischia | Theropoda | Coelurosauria | Aves | Neognathae | Accipitriformes | Accipitridae
#> 94                                                                                                                    Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Laurasiatheria | Scrotifera | Carnivora | Caniformia | Canidae
#> 95                                                                                                                          root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Feliformia | Felidae
#> 96                                                                              root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Hominoidea | Hominidae
#> 97                                                                                                                                                                                                                                                                                                                                                                                                                                                                           <NA>
#> 98                                                                                                                                                                                                                                                                                                                                                              root | cellular organisms | Bacteria | Proteobacteria | Gammaproteobacteria | Vibrionales | Vibrionaceae | Vibrio
#> 99                                                                                                                       Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Reptilia | Diapsida | Lepidosauromorpha | Lepidosauria | Squamata | Serpentes | Alethinophidia | Viperidae | Crotalinae | Agkistrodon | Agkistrodon contortrix
#> 100                                                                                                                             root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Sauropsida | Sauria | Archelosauria | Archosauria | Crocodylia | Longirostres | Crocodylidae
#> 101                                                                              root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Feliformia | Felidae | Pantherinae | Panthera | Panthera pardus
#> 102                                                                                                                         root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Feliformia | Felidae
#> 103                                                                                          Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Laurasiatheria | Scrotifera | Carnivora | Feliformia | Felidae | Pantherinae | Panthera
#> 104                                                                              root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Feliformia | Felidae | Pantherinae | Panthera | Panthera tigris
#> 105                                                                                                                                                root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora
#> 106                                                                                               root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Strepsirrhini | Lemuriformes | Cheirogaleidae
#> 107                                                                              root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Feliformia | Felidae | Pantherinae | Panthera | Panthera tigris
#> 108                                                                              root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Feliformia | Felidae | Pantherinae | Panthera | Panthera pardus
#> 109                                                                                          Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Laurasiatheria | Scrotifera | Carnivora | Feliformia | Felidae | Pantherinae | Panthera
#> 110                                      root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Sauropsida | Sauria | Archelosauria | Archosauria | Dinosauria | Saurischia | Theropoda | Coelurosauria | Aves | Neognathae | Accipitriformes | Accipitridae | Accipitrinae | Buteo
#> 111                                                                                                                                                                                                                                                                                                                                                                                                                                                                          <NA>
#> 112                                                                                             Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Laurasiatheria | Scrotifera | Carnivora | Caniformia | Canidae | Cuon | Cuon alpinus
#> 113                                     root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Sauropsida | Sauria | Archelosauria | Archosauria | Dinosauria | Saurischia | Theropoda | Coelurosauria | Aves | Neognathae | Accipitriformes | Accipitridae | Accipitrinae | Aquila
#> 114                                                                                              root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Caniformia | Ursidae | Ursus | Ursus thibetanus
#> 115                                  root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Sauropsida | Sauria | Archelosauria | Archosauria | Dinosauria | Saurischia | Theropoda | Coelurosauria | Aves | Neognathae | Accipitriformes | Accipitridae | Accipitrinae | Accipiter
#> 116                                                                                                                                                                                                                                               Boreoeutheria | Laurasiatheria | Scrotifera | Ferungulata | Ferae | Pan-Carnivora | Carnivoramorpha | Carnivoraformes | Carnivora | Feliformia | Felidae | Pantherinae | Panthera | Panthera tigris | Panthera tigris amoyensis
#> 117                                                                                                            Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Laurasiatheria | Scrotifera | Carnivora | Caniformia | Canidae | Cuon
#> 118                                     root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Sauropsida | Sauria | Archelosauria | Archosauria | Dinosauria | Saurischia | Theropoda | Coelurosauria | Aves | Neognathae | Accipitriformes | Accipitridae | Accipitrinae | Milvus
#> 119             root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Sauropsida | Sauria | Archelosauria | Archosauria | Dinosauria | Saurischia | Theropoda | Coelurosauria | Aves | Neognathae | Accipitriformes | Accipitridae | Accipitrinae | Accipiter | Accipiter gentilis
#> 120                                                                                                                 root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Caniformia | Canidae | Canis
#> 121                                                                               root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Feliformia | Felidae | Pantherinae | Panthera | Panthera uncia
#> 122                 root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Sauropsida | Sauria | Archelosauria | Archosauria | Dinosauria | Saurischia | Theropoda | Coelurosauria | Aves | Neognathae | Accipitriformes | Accipitridae | Accipitrinae | Aquila | Aquila chrysaetos
#> 123                                                                                                                 root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Caniformia | Ursidae | Ursus
#> 124                                                                                                                                                                                                                                                                     Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 125                                                                             root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Hominoidea | Hominidae
#> 126                                                             root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Sauropsida | Sauria | Archelosauria | Archosauria | Dinosauria | Saurischia | Theropoda | Coelurosauria | Aves | Neognathae | Accipitriformes | Accipitridae
#> 127                                                                                                                         root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Feliformia | Felidae
#> 128                                                                                                                   Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Laurasiatheria | Scrotifera | Carnivora | Caniformia | Canidae
#> 129                                                                                                                         root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Feliformia | Felidae
#> 130                                                                                                                   Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Laurasiatheria | Scrotifera | Carnivora | Caniformia | Canidae
#> 131                                                             root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Sauropsida | Sauria | Archelosauria | Archosauria | Dinosauria | Saurischia | Theropoda | Coelurosauria | Aves | Neognathae | Accipitriformes | Accipitridae
#> 132                                                                             root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Hominoidea | Hominidae
#> 133                                                                                                                                                                                                                                                                                                                                               Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Reptilia | Crocodylia | Alligatoridae
#> 134                                                                                                                      root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Caniformia | Mustelidae
#> 135                                                                                                                                                                                                                                                                     Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 136                                                                                                                                                                                                                                                                      Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Pan
#> 137                                                                                                                                                                                                                                                                     Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 138                                                                                                                         root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Feliformia | Felidae
#> 139                                                                                          Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Laurasiatheria | Scrotifera | Carnivora | Feliformia | Felidae | Pantherinae | Panthera
#> 140                                                                                                                                                                                                                                                                     Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 141                                                                                          Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Laurasiatheria | Scrotifera | Carnivora | Feliformia | Felidae | Pantherinae | Panthera
#> 142                                                                                                                                                                                                                                                                                                                          Theria | Placentalia | Boreoeutheria | Laurasiatheria | Carnivora | Caniformia | Canoidea |  |  | Canidae |  |  | Canis |  | familiaris | familiaris
#> 143                                                                                                                                                                                                                                                                                          Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Reptilia | Squamata | Serpentes | Alethinophidia | Pythonidae | Python | Python natalensis
#> 144                                      root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Sauropsida | Sauria | Archelosauria | Archosauria | Dinosauria | Saurischia | Theropoda | Coelurosauria | Aves | Neognathae | Accipitriformes | Accipitridae | Accipitrinae | Buteo
#> 145                                                             root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Sauropsida | Sauria | Archelosauria | Archosauria | Dinosauria | Saurischia | Theropoda | Coelurosauria | Aves | Neognathae | Accipitriformes | Accipitridae
#> 146                                                                                                            root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Sauropsida | Sauria | Lepidosauria | Squamata | Bifurcata | Unidentata | Episquamata | Toxicofera | Serpentes
#> 147                                                                              root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Feliformia | Felidae | Pantherinae | Panthera | Panthera pardus
#> 148                                                                                                                                                                                                                                                                     Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 149                                                                                                                                                                                                                                                                      Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Pan
#> 150                                                                             root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Hominoidea | Hominidae
#> 151                                                                                                            root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Sauropsida | Sauria | Lepidosauria | Squamata | Bifurcata | Unidentata | Episquamata | Toxicofera | Serpentes
#> 152                                                                                         root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Feliformia | Felidae | Felinae | Felis | Felis catus
#> 153                                                                                                                                                                                                                                                                     Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 154                                                                                                                   Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Laurasiatheria | Scrotifera | Carnivora | Caniformia | Canidae
#> 155                                                                                                                         root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Feliformia | Felidae
#> 156                                                                                                                 root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Caniformia | Canidae | Canis
#> 157                                                                          root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Caniformia | Canidae | Canis | Canis lupus | Canis lupus familiaris
#> 158                                                                                                                                                                                                                                                                                                    Boreoeutheria | Laurasiatheria | Scrotifera | Ferungulata | Ferae | Pan-Carnivora | Carnivoramorpha | Carnivoraformes | Carnivora | Feliformia | Herpestoidea | Eupleridae
#> 159                                                                     root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Feliformia | Eupleridae | Euplerinae | Cryptoprocta | Cryptoprocta ferox
#> 160                                                                                                                                                                                                                                                                     Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 161                                                                                                                                                                                                                                                                     Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 162                                                                                                                                                                                                                                                                     Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 163                                                                                                                                                                                                                                                                     Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 164                                                                                                                                                                                                                                                                     Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 165                                                                                                                           Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Reptilia | Diapsida | Lepidosauromorpha | Lepidosauria | Squamata | Serpentes | Alethinophidia | Sanziniidae | Acrantophis | Acrantophis madagascariensis
#> 166                                                                                                                                                                                                                                                                             Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Reptilia | Squamata | Serpentes | Alethinophidia | Pythonidae | Malayopython | Malayopython reticulatus
#> 167                                                                                                                                                                                                                                                                     Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 168 root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Actinopterygii | Actinopteri | Neopterygii | Teleostei | Osteoglossocephalai | Clupeocephala | Euteleosteomorpha | Neoteleostei | Eurypterygia | Ctenosquamata | Acanthomorphata | Euacanthomorphacea | Percomorphaceae | Eupercaria | Perciformes | Cottioidei | Cottales | Agonidae
#> 169                                                                                                                                                                                                                                                                            Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Carnivora | Feliformia | Felidae | Pantherinae | Panthera | Panthera onca
#> 170                                                                                          Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Synapsida | Therapsida | Cynodontia | Mammalia | Theria | Eutheria | Placentalia | Boreoeutheria | Laurasiatheria | Scrotifera | Carnivora | Feliformia | Felidae | Pantherinae | Panthera
#> 171                                                                                                                                                                                                                                                                     Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 172                    root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Sauropsida | Sauria | Archelosauria | Archosauria | Dinosauria | Saurischia | Theropoda | Coelurosauria | Aves | Neognathae | Accipitriformes | Accipitridae | Accipitrinae | Harpia | Harpia harpyja
#> 173                                                                                                                                                                                                                                                                     Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 174                                                                                                                                                                                                                                                                     Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 175                      root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Protostomia | Ecdysozoa | Panarthropoda | Arthropoda | Mandibulata | Pancrustacea | Hexapoda | Insecta | Dicondylia | Pterygota | Neoptera | Endopterygota | Amphiesmenoptera | Lepidoptera | Glossata | Neolepidoptera | Heteroneura | Ditrysia | Obtectomera | Papilionoidea | Nymphalidae | Danainae | Danaini | Danaina | Danaus | Anosia | Danaus eresimus
#> 176                                           root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 177                                                                                                                                                                                                                                                                     Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 178                                                                                                                         root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Feliformia | Felidae
#> 179                                                                             root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Hominoidea | Hominidae
#> 180                                                                                                                                                                                                                                                                     Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 181    root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Sauropsida | Sauria | Archelosauria | Archosauria | Dinosauria | Saurischia | Theropoda | Coelurosauria | Aves | Neognathae | Accipitriformes | Accipitridae | Accipitrinae | Stephanoaetus | Stephanoaetus coronatus
#> 182                                                                              root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Feliformia | Felidae | Pantherinae | Panthera | Panthera pardus
#> 183                                                                                                                                                                                                                                                                     Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 184                                                                                                                                                                                                                                                                     Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 185                                                                                                                                                                                                                                                                     Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 186                                                                                                                                                                                                                                                                     Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo
#> 187                                                                                                                         root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Feliformia | Felidae
#> 188                                                                                                                                                                                                                                                                                                                                                                                                                                       Accipitriformes | Accipitridae | Harpia
#> 189                                                 root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Protostomia | Ecdysozoa | Panarthropoda | Arthropoda | Mandibulata | Pancrustacea | Hexapoda | Insecta | Dicondylia | Pterygota | Neoptera | Endopterygota | Amphiesmenoptera | Lepidoptera | Glossata | Neolepidoptera | Heteroneura | Ditrysia | Obtectomera | Papilionoidea | Nymphalidae | Danainae | Danaini | Danaina | Danaus
#> 190                      root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Protostomia | Ecdysozoa | Panarthropoda | Arthropoda | Mandibulata | Pancrustacea | Hexapoda | Insecta | Dicondylia | Pterygota | Neoptera | Endopterygota | Amphiesmenoptera | Lepidoptera | Glossata | Neolepidoptera | Heteroneura | Ditrysia | Obtectomera | Papilionoidea | Nymphalidae | Danainae | Danaini | Danaina | Danaus | Anosia | Danaus eresimus
#> 191                                                                                                                                                                                                                                                      Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 192        root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Euarchontoglires | Primates | Haplorrhini | Simiiformes | Catarrhini | Hominoidea | Hominidae | Homininae | Pan | Pan troglodytes | Pan troglodytes schweinfurthii
#> 193                                                                                                                                                                                                                                                                                                                                                                                                      Accipitriformes | Accipitridae | Stephanoaetus | Stephanoaetus coronatus
#> 194                                                                                                                                                                                                                                                      Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 195                                                                                                                                                                                                                                                      Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 196                                                                                                                                                                                                                                                      Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 197                                                                                                                                                                                                                                                                                                            Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Reptilia | Crocodylia | Crocodylidae | Crocodylus | Crocodylus niloticus
#> 198                                                                                                                                                                                                                                                                                                                                                                                                           Accipitriformes | Accipitridae | Polemaetus | Polemaetus bellicosus
#> 199                                                                                                                                                                                                                                                      Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 200                                                                                                                                                                                                                                                      Eukaryota | Animalia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Tetrapoda | Mammalia | Theria | Eutheria | Primates | Haplorrhini | Simiiformes | Hominoidea | Hominidae | Homininae | Homo | Homo sapiens
#> 201                                                                              root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Mammalia | Theria | Eutheria | Boreoeutheria | Laurasiatheria | Carnivora | Feliformia | Felidae | Pantherinae | Panthera | Panthera pardus
#> 202    root | cellular organisms | Eukaryota | Opisthokonta | Metazoa | Eumetazoa | Bilateria | Deuterostomia | Chordata | Craniata | Vertebrata | Gnathostomata | Teleostomi | Euteleostomi | Sarcopterygii | Dipnotetrapodomorpha | Tetrapoda | Amniota | Sauropsida | Sauria | Archelosauria | Archosauria | Dinosauria | Saurischia | Theropoda | Coelurosauria | Aves | Neognathae | Accipitriformes | Accipitridae | Accipitrinae | Stephanoaetus | Stephanoaetus coronatus
#> 203                                                                                                                                   Life | Cellular Organisms | Eukaryota | Opisthokonta | Metazoa | Bilateria | Deuterostomia | Chordata | Vertebrata | Gnathostomata | Osteichthyes | Sarcopterygii | Tetrapoda | Amniota | Reptilia | Diapsida | Lepidosauromorpha | Lepidosauria | Squamata | Serpentes | Alethinophidia | Sanziniidae | Acrantophis | Acrantophis dumerili
#> 204                                                                                                                                                                                                                                                                                                                                                                                                                                                                          <NA>
#>     target_specimen_life_stage latitude longitude study_citation
#> 1                           NA       NA        NA             NA
#> 2                           NA       NA        NA             NA
#> 3                           NA       NA        NA             NA
#> 4                           NA       NA        NA             NA
#> 5                           NA       NA        NA             NA
#> 6                           NA       NA        NA             NA
#> 7                           NA       NA        NA             NA
#> 8                           NA       NA        NA             NA
#> 9                           NA       NA        NA             NA
#> 10                          NA       NA        NA             NA
#> 11                          NA       NA        NA             NA
#> 12                          NA       NA        NA             NA
#> 13                          NA       NA        NA             NA
#> 14                          NA       NA        NA             NA
#> 15                          NA       NA        NA             NA
#> 16                          NA       NA        NA             NA
#> 17                          NA       NA        NA             NA
#> 18                          NA       NA        NA             NA
#> 19                          NA       NA        NA             NA
#> 20                          NA       NA        NA             NA
#> 21                          NA       NA        NA             NA
#> 22                          NA       NA        NA             NA
#> 23                          NA       NA        NA             NA
#> 24                          NA       NA        NA             NA
#> 25                          NA       NA        NA             NA
#> 26                          NA       NA        NA             NA
#> 27                          NA       NA        NA             NA
#> 28                          NA       NA        NA             NA
#> 29                          NA       NA        NA             NA
#> 30                          NA       NA        NA             NA
#> 31                          NA       NA        NA             NA
#> 32                          NA       NA        NA             NA
#> 33                          NA       NA        NA             NA
#> 34                          NA       NA        NA             NA
#> 35                          NA       NA        NA             NA
#> 36                          NA       NA        NA             NA
#> 37                          NA       NA        NA             NA
#> 38                          NA       NA        NA             NA
#> 39                          NA       NA        NA             NA
#> 40                          NA       NA        NA             NA
#> 41                          NA       NA        NA             NA
#> 42                          NA       NA        NA             NA
#> 43                          NA       NA        NA             NA
#> 44                          NA       NA        NA             NA
#> 45                          NA       NA        NA             NA
#> 46                          NA       NA        NA             NA
#> 47                          NA       NA        NA             NA
#> 48                          NA       NA        NA             NA
#> 49                          NA       NA        NA             NA
#> 50                          NA       NA        NA             NA
#> 51                          NA       NA        NA             NA
#> 52                          NA       NA        NA             NA
#> 53                          NA       NA        NA             NA
#> 54                          NA       NA        NA             NA
#> 55                          NA       NA        NA             NA
#> 56                          NA       NA        NA             NA
#> 57                          NA       NA        NA             NA
#> 58                          NA       NA        NA             NA
#> 59                          NA       NA        NA             NA
#> 60                          NA       NA        NA             NA
#> 61                          NA       NA        NA             NA
#> 62                          NA       NA        NA             NA
#> 63                          NA       NA        NA             NA
#> 64                          NA       NA        NA             NA
#> 65                          NA       NA        NA             NA
#> 66                          NA       NA        NA             NA
#> 67                          NA       NA        NA             NA
#> 68                          NA       NA        NA             NA
#> 69                          NA       NA        NA             NA
#> 70                          NA       NA        NA             NA
#> 71                          NA       NA        NA             NA
#> 72                          NA       NA        NA             NA
#> 73                          NA       NA        NA             NA
#> 74                          NA       NA        NA             NA
#> 75                          NA       NA        NA             NA
#> 76                          NA       NA        NA             NA
#> 77                          NA       NA        NA             NA
#> 78                          NA       NA        NA             NA
#> 79                          NA       NA        NA             NA
#> 80                          NA       NA        NA             NA
#> 81                          NA       NA        NA             NA
#> 82                          NA       NA        NA             NA
#> 83                          NA       NA        NA             NA
#> 84                          NA       NA        NA             NA
#> 85                          NA       NA        NA             NA
#> 86                          NA       NA        NA             NA
#> 87                          NA       NA        NA             NA
#> 88                          NA       NA        NA             NA
#> 89                          NA       NA        NA             NA
#> 90                          NA       NA        NA             NA
#> 91                          NA       NA        NA             NA
#> 92                          NA       NA        NA             NA
#> 93                          NA       NA        NA             NA
#> 94                          NA       NA        NA             NA
#> 95                          NA       NA        NA             NA
#> 96                          NA       NA        NA             NA
#> 97                          NA       NA        NA             NA
#> 98                          NA       NA        NA             NA
#> 99                          NA       NA        NA             NA
#> 100                         NA       NA        NA             NA
#> 101                         NA       NA        NA             NA
#> 102                         NA       NA        NA             NA
#> 103                         NA       NA        NA             NA
#> 104                         NA       NA        NA             NA
#> 105                         NA       NA        NA             NA
#> 106                         NA       NA        NA             NA
#> 107                         NA       NA        NA             NA
#> 108                         NA       NA        NA             NA
#> 109                         NA       NA        NA             NA
#> 110                         NA       NA        NA             NA
#> 111                         NA       NA        NA             NA
#> 112                         NA       NA        NA             NA
#> 113                         NA       NA        NA             NA
#> 114                         NA       NA        NA             NA
#> 115                         NA       NA        NA             NA
#> 116                         NA       NA        NA             NA
#> 117                         NA       NA        NA             NA
#> 118                         NA       NA        NA             NA
#> 119                         NA       NA        NA             NA
#> 120                         NA       NA        NA             NA
#> 121                         NA       NA        NA             NA
#> 122                         NA       NA        NA             NA
#> 123                         NA       NA        NA             NA
#> 124                         NA       NA        NA             NA
#> 125                         NA       NA        NA             NA
#> 126                         NA       NA        NA             NA
#> 127                         NA       NA        NA             NA
#> 128                         NA       NA        NA             NA
#> 129                         NA       NA        NA             NA
#> 130                         NA       NA        NA             NA
#> 131                         NA       NA        NA             NA
#> 132                         NA       NA        NA             NA
#> 133                         NA       NA        NA             NA
#> 134                         NA       NA        NA             NA
#> 135                         NA       NA        NA             NA
#> 136                         NA       NA        NA             NA
#> 137                         NA       NA        NA             NA
#> 138                         NA       NA        NA             NA
#> 139                         NA       NA        NA             NA
#> 140                         NA       NA        NA             NA
#> 141                         NA       NA        NA             NA
#> 142                         NA       NA        NA             NA
#> 143                         NA       NA        NA             NA
#> 144                         NA       NA        NA             NA
#> 145                         NA       NA        NA             NA
#> 146                         NA       NA        NA             NA
#> 147                         NA       NA        NA             NA
#> 148                         NA       NA        NA             NA
#> 149                         NA       NA        NA             NA
#> 150                         NA       NA        NA             NA
#> 151                         NA       NA        NA             NA
#> 152                         NA       NA        NA             NA
#> 153                         NA       NA        NA             NA
#> 154                         NA       NA        NA             NA
#> 155                         NA       NA        NA             NA
#> 156                         NA       NA        NA             NA
#> 157                         NA       NA        NA             NA
#> 158                         NA       NA        NA             NA
#> 159                         NA       NA        NA             NA
#> 160                         NA       NA        NA             NA
#> 161                         NA       NA        NA             NA
#> 162                         NA       NA        NA             NA
#> 163                         NA       NA        NA             NA
#> 164                         NA       NA        NA             NA
#> 165                         NA       NA        NA             NA
#> 166                         NA       NA        NA             NA
#> 167                         NA       NA        NA             NA
#> 168                         NA       NA        NA             NA
#> 169                         NA       NA        NA             NA
#> 170                         NA       NA        NA             NA
#> 171                         NA       NA        NA             NA
#> 172                         NA       NA        NA             NA
#> 173                         NA       NA        NA             NA
#> 174                         NA       NA        NA             NA
#> 175                         NA       NA        NA             NA
#> 176                         NA       NA        NA             NA
#> 177                         NA       NA        NA             NA
#> 178                         NA       NA        NA             NA
#> 179                         NA       NA        NA             NA
#> 180                         NA       NA        NA             NA
#> 181                         NA       NA        NA             NA
#> 182                         NA       NA        NA             NA
#> 183                         NA       NA        NA             NA
#> 184                         NA       NA        NA             NA
#> 185                         NA       NA        NA             NA
#> 186                         NA       NA        NA             NA
#> 187                         NA       NA        NA             NA
#> 188                         NA       NA        NA             NA
#> 189                         NA       NA        NA             NA
#> 190                         NA       NA        NA             NA
#> 191                         NA       NA        NA             NA
#> 192                         NA       NA        NA             NA
#> 193                         NA       NA        NA             NA
#> 194                         NA       NA        NA             NA
#> 195                         NA       NA        NA             NA
#> 196                         NA       NA        NA             NA
#> 197                         NA       NA        NA             NA
#> 198                         NA       NA        NA             NA
#> 199                         NA       NA        NA             NA
#> 200                         NA       NA        NA             NA
#> 201                         NA       NA        NA             NA
#> 202                         NA       NA        NA             NA
#> 203                         NA       NA        NA             NA
#> 204                         NA       NA        NA             NA
#>     study_source_citation
#> 1                      NA
#> 2                      NA
#> 3                      NA
#> 4                      NA
#> 5                      NA
#> 6                      NA
#> 7                      NA
#> 8                      NA
#> 9                      NA
#> 10                     NA
#> 11                     NA
#> 12                     NA
#> 13                     NA
#> 14                     NA
#> 15                     NA
#> 16                     NA
#> 17                     NA
#> 18                     NA
#> 19                     NA
#> 20                     NA
#> 21                     NA
#> 22                     NA
#> 23                     NA
#> 24                     NA
#> 25                     NA
#> 26                     NA
#> 27                     NA
#> 28                     NA
#> 29                     NA
#> 30                     NA
#> 31                     NA
#> 32                     NA
#> 33                     NA
#> 34                     NA
#> 35                     NA
#> 36                     NA
#> 37                     NA
#> 38                     NA
#> 39                     NA
#> 40                     NA
#> 41                     NA
#> 42                     NA
#> 43                     NA
#> 44                     NA
#> 45                     NA
#> 46                     NA
#> 47                     NA
#> 48                     NA
#> 49                     NA
#> 50                     NA
#> 51                     NA
#> 52                     NA
#> 53                     NA
#> 54                     NA
#> 55                     NA
#> 56                     NA
#> 57                     NA
#> 58                     NA
#> 59                     NA
#> 60                     NA
#> 61                     NA
#> 62                     NA
#> 63                     NA
#> 64                     NA
#> 65                     NA
#> 66                     NA
#> 67                     NA
#> 68                     NA
#> 69                     NA
#> 70                     NA
#> 71                     NA
#> 72                     NA
#> 73                     NA
#> 74                     NA
#> 75                     NA
#> 76                     NA
#> 77                     NA
#> 78                     NA
#> 79                     NA
#> 80                     NA
#> 81                     NA
#> 82                     NA
#> 83                     NA
#> 84                     NA
#> 85                     NA
#> 86                     NA
#> 87                     NA
#> 88                     NA
#> 89                     NA
#> 90                     NA
#> 91                     NA
#> 92                     NA
#> 93                     NA
#> 94                     NA
#> 95                     NA
#> 96                     NA
#> 97                     NA
#> 98                     NA
#> 99                     NA
#> 100                    NA
#> 101                    NA
#> 102                    NA
#> 103                    NA
#> 104                    NA
#> 105                    NA
#> 106                    NA
#> 107                    NA
#> 108                    NA
#> 109                    NA
#> 110                    NA
#> 111                    NA
#> 112                    NA
#> 113                    NA
#> 114                    NA
#> 115                    NA
#> 116                    NA
#> 117                    NA
#> 118                    NA
#> 119                    NA
#> 120                    NA
#> 121                    NA
#> 122                    NA
#> 123                    NA
#> 124                    NA
#> 125                    NA
#> 126                    NA
#> 127                    NA
#> 128                    NA
#> 129                    NA
#> 130                    NA
#> 131                    NA
#> 132                    NA
#> 133                    NA
#> 134                    NA
#> 135                    NA
#> 136                    NA
#> 137                    NA
#> 138                    NA
#> 139                    NA
#> 140                    NA
#> 141                    NA
#> 142                    NA
#> 143                    NA
#> 144                    NA
#> 145                    NA
#> 146                    NA
#> 147                    NA
#> 148                    NA
#> 149                    NA
#> 150                    NA
#> 151                    NA
#> 152                    NA
#> 153                    NA
#> 154                    NA
#> 155                    NA
#> 156                    NA
#> 157                    NA
#> 158                    NA
#> 159                    NA
#> 160                    NA
#> 161                    NA
#> 162                    NA
#> 163                    NA
#> 164                    NA
#> 165                    NA
#> 166                    NA
#> 167                    NA
#> 168                    NA
#> 169                    NA
#> 170                    NA
#> 171                    NA
#> 172                    NA
#> 173                    NA
#> 174                    NA
#> 175                    NA
#> 176                    NA
#> 177                    NA
#> 178                    NA
#> 179                    NA
#> 180                    NA
#> 181                    NA
#> 182                    NA
#> 183                    NA
#> 184                    NA
#> 185                    NA
#> 186                    NA
#> 187                    NA
#> 188                    NA
#> 189                    NA
#> 190                    NA
#> 191                    NA
#> 192                    NA
#> 193                    NA
#> 194                    NA
#> 195                    NA
#> 196                    NA
#> 197                    NA
#> 198                    NA
#> 199                    NA
#> 200                    NA
#> 201                    NA
#> 202                    NA
#> 203                    NA
#> 204                    NA
# }
```
