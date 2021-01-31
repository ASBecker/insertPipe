## Synopsis

Allows configuration of RStudio to insert the magrittr assignment pipe (%<>%) at the current cursor position

## Motivation

The %<>% pipe form the [magrittr](https://github.com/tidyverse/magrittr) package is a very useful tool to create human-readable and reproducible code. Mapping it to a keyboard shortcut saves significant time during coding.

## Installation

``` r
install.packages("remotes")
remotes::install_github("ASBecker/insertPipe")
```
Then map the addin to a keyboard shortcut in RStudio.

## Acknowledgements

Thanks to the magrittr developers and contributors

## License

CC BY 4.0
