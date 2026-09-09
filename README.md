# inedemogR <img src="man/figures/logo.png" align="right" width="150" alt="inedemogR hex logo" />

<!-- badges: start -->
![R build status](https://github.com/jrcarob/inedemogR_package/actions/workflows/R-CMD-check.yaml/badge.svg)
<!-- badges: end -->

__inedemogR__ provides tidy access to demographic data from the Spanish National Statistics
Institute (INE), specifically its "fenómenos demográficos" domain: population, births, and
deaths. Data is retrieved live via the official `ineapir` API wrapper and tidied into
long/wide data frames, with optional spatial integration via `mapSpain` and `sf`.

## Installation

```r
# CRAN
install.packages("inedemogR")

# development version
pak::pak("jrcarob/inedemogR_package")
```

Package source and issues: <https://github.com/jrcarob/inedemogR_package>.
