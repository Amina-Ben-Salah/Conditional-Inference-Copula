# Copula-Conditional-Inference-R

This repository contains code to model the joint distribution of sea surface temperature (SST) and chlorophyll-a (Chl) data using copulas. The main objective is to simulate chlorophyll-a values conditioned on forecasted SST values.

## Requirements

- R (version 4.0.0 or higher)
- Required R packages:
  - `copula`
  - `VC2copula`
  - `extRemes`
  - `ordinal`
  - `readxl`
  - `VineCopula`

You can install the required packages using the following commands:

```r
install.packages(c("copula", "VC2copula", "extRemes", "ordinal", "readxl", "VineCopula"))
