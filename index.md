# inedemogR <img src="man/figures/logo.png" width = "250px" align = "right" alt="inedemogR hex logo" />

[![CRAN status](https://www.r-pkg.org/badges/version/inedemogR)](https://CRAN.R-project.org/package=inedemogR)
[![CRAN downloads](https://cranlogs.r-pkg.org/badges/inedemogR)](https://CRAN.R-project.org/package=inedemogR)

__inedemogR__ provides tidy access to demographic data from the Spanish National Statistics
Institute (INE), specifically its "fenómenos demográficos" domain: population, births, and
deaths. Data is retrieved live via the official `ineapir` API wrapper and tidied into
long/wide data frames, with optional spatial integration via `mapSpain` and `sf`.

A stable version of this package is available on CRAN and can be installed directly from there:

```r
install.packages("inedemogR")
```

The latest development version of the package can also be loaded directly from GitHub:

```r
# install.packages("pak")
pak::pak("jrcarob/inedemogR_package")
```

or

```r
# install.packages("devtools")
devtools::install_github("jrcarob/inedemogR_package")
```

To learn more about how the package works, read through the following articles:

* [Basic usage of __inedemogR__](articles/basic-usage.html)
