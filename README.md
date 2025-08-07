# Tidy Manipulation of Genomic Data


This tutorial is meant to be run with Bioconductor Version 3.21.

Required packages include:

* `tidySummarizedExperiment`
* `plyxp` (v 1.2.7)
* `dplyr`
* `ggplot2`


## Package Installation

`plyxp` had a few patches in preparation for this tutorial. As they have not yet been built on Bioconductor, you will need to install it directly from GitHub.

```r
# install.packages("remotes")
remotes::install_github("jtlandis/plyxp@RELEASE_3_21")
```

You can install `tidySummarizedExperiment` from Bioconductor:

```r
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
}
BiocManager::install("tidySummarizedExperiment")
```

Other tidyverse packages may be installed along side of `tidySummarizedExperiment`, but please ensure you have at least `dplyr` and `ggplot2` installed.

```r
install.packages(c("dplyr", "ggplot2"))
```
