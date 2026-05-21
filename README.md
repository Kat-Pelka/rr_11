# RR Assignment 11

This project demonstrates a reproducible R environment using `renv`.

## Project contents

* `analysis.R` – example analysis script
* `renv.lock` – dependency lockfile
* `renv/` – renv infrastructure

## Required packages

* ggplot2
* dplyr

## Reproducing the environment

1. Clone the repository:

```bash
git clone https://github.com/Kat-Pelka/rr_11
```

2. Open the project in RStudio.

3. Install renv if needed:

```r
install.packages("renv")
```

4. Restore the environment:

```r
renv::restore()
```

5. Run the script:

```r
source("analysis.R")
```
