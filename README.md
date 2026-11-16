# laercio

Duncan, Tukey and Scott-Knott tests to compare and group means from fitted analysis of variance models.

Compatibility updates by Renova.

Version 1.0.1.9001: `NAMESPACE` imports `pchisq` and `qtukey` from stats and `read.table` from utils, which the package calls, and the DESCRIPTION title case, `Authors@R`, Description wording and stale `Date` are updated. R function bodies are unchanged.

## Install

```r
install.packages("laercio", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

See the [R-universe package page](https://renova-r.r-universe.dev/laercio) for builds and installation. This release is tagged on GitHub as `renova-1.0.1.9001`:

```r
remotes::install_github("renova-r/laercio@renova-1.0.1.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

laercio is by Laercio Junio da Silva; the original CRAN package is at <https://CRAN.R-project.org/package=laercio>. License: GPL (>= 3); see [COPYING](COPYING).
