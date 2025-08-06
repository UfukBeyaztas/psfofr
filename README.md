# psfofr <img src="https://img.shields.io/badge/R-%3E=3.5.0-1f425f.svg" alt="R (>= 3.5.0)" align="right" height="20"/>

[![R-CMD-check](https://github.com/UfukBeyaztas/psfofr/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/UfukBeyaztas/psfofr/actions/workflows/R-CMD-check.yaml)
[![License: GPL-3](https://img.shields.io/badge/License-GPL--3-blue.svg)](LICENSE)

**Penalized Spatial Function-on-Function Regression** (PSFoFR).  
It implements the **Penalized Spatial Two-Stage Least Squares (Pen2SLS)** estimator, coupling tensor-product B-splines with spatial autoregression to produce smooth, interpretable surfaces and reliable inference even under strong spatial dependence.

---

## Installation

```r
# install devtools if you don't have it
install.packages("devtools")

# install the development version from GitHub
library(devtools)
install_github("UfukBeyaztas/psfofr")

**Package manual**
Please see psfofr_1.0.pdf file for package manual.

