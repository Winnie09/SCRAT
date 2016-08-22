SCRAT: Single-Cell Regulome Analysis Tool
====

## SCRAT Installation

SCRAT software can be installed via Github.
Users should have R installed on their computer before installing SCRAT. R can be downloaded here: http://www.r-project.org/.
Users should first install the SCRAT data packages by running following commands in R:
```{r }
if (!require("devtools"))
  install.packages("devtools")
devtools::install_github("SCRATdatahg19","zji90")
devtools::install_github("SCRATdatahg38","zji90")
devtools::install_github("SCRATdatamm10","zji90")
devtools::install_github("SCRATdatamm9","zji90")
```

To install the latest version of SCRAT package via Github, run following commands in R:
```{r }
source("https://bioconductor.org/biocLite.R")
biocLite("GenomicAlignments")
if (!require("devtools"))
  install.packages("devtools")
devtools::install_github("SCRAT","zji90")
```
To launch user interface after installation, run following commands in R:
```{r }
library(SCRAT)
SCRATui()
```

## SCRAT Online User Interface

SCRAT is also available online at https://zhiji.shinyapps.io/scrat/

## SCRAT User Manual

SCRAT user manual is available on Github: https://github.com/zji90/SCRATdata/blob/master/manual.pdf

## Contact the Author
Author: Zhicheng Ji, Weiqiang Zhou, Hongkai Ji

Report bugs and provide suggestions by sending email to:

Maintainer: Zhicheng Ji (zji4@jhu.edu)

Or open a new issue on this Github page
