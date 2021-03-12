Install and Load R packages
================

## Using `pacman` package:

The function `p_load()` checks if a package is installed, if not , it
installs the package and then loads it.

``` r
# install.packages("pacman")

pacman::p_load(ggplot2, tidyr, dplyr)
```

## Using `librarian` package:

The function `shelf()` automatically installs, updates and loads R
packages that are not yet installed.

``` r
# install.packages("librarian")

librarian::shelf(ggplot2)
```

    ## 
    ##   The 'cran_repo' argument in shelf() was not set, so it will use
    ##   cran_repo = 'https://cran.r-project.org' by default.
    ## 
    ##   To avoid this message, set the 'cran_repo' argument to a CRAN
    ##   mirror URL (see https://cran.r-project.org/mirrors.html) or set
    ##   'quiet = TRUE'.

### References

-   Article -
    <https://statsandr.com/blog/an-efficient-way-to-install-and-load-r-packages/>
