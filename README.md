Arqiv2
====

Arqiv2 is a R package for Real-Time Data Analysis of Compounds Performance Relative to Controls in Primary Screening.

## Overview

The Arqiv2 package allows the user to plot signal to background ratios, strictly standardized mean difference (SSMD) scores, microplate heat map and generate SSMD score table of each compound.

The Arqiv2 package is a part of the paper "Large-scale Phenotypic Drug Screen Identifies Neuroprotectants in Zebrafish and Mouse Models of Retinitis Pigmentosa".

## Package Installation
* STEP 1:  Install the latest version of R(for Windows (https://cran.r-project.org/bin/windows/base/) or Mac(https://cran.r-project.org/bin/macosx/)) and RStudio(https://www.rstudio.com/products/rstudio/download2/) on your computer. R version 3.6.3 is prefered. 
* STEP 2: To install Arqiv2 package via Github, the user must have installed [Rtools](https://cran.r-project.org/bin/windows/Rtools/) and [devtools](https://cran.r-project.org/web/packages/devtools/index.html) by running the following commands in RStudio Console window:
```{r}
install.packages("devtools")
install.packages("usethis")
library(devtools)
```

* STEP 3: To use the graphical user interface (GUI) in Arqiv2 package, the user must have first installed RGtk2, GTK2+  with commands in RStudio Console.

##### STEP 3a: for Windows
```{r}
install.packages("RGtk2",depen=T)
library(RGtk2)
```
There will be a notice for missing GTK. Choose "Install GTK+" when prompted - this will take ~1 minute to complete. Afterwards the user needs to restart R/Rstudio.

##### STEP 3b: for Mac
Install [GTK 2.24](http://r.research.att.com/libs/GTK_2.24.17-X11.pkg). And use command
```{r}
install.packages("RGtk2",depen=T)
```
in RStudio console window. Then user need to restart R/Rstudio.

* STEP 4: Complete RGtk2,gWidgets2RGtk2 packages installation by commands in RStudio console window:
```{r}
library(RGtk2)
install.packages("gWidgets2RGtk2")
library(gWidgets2RGtk2)
```

* STEP 5: Install Arqiv2 package and open GUI window with the following command in RStudio console window:
```{r}
devtools::install_github("mummlab/Arqiv2")
library(Arqiv2)
GUI()
```

## Further questions
Author:  Liyun Zhang, Ding Ding

Any questions about the package, please contact
Maintainer: Liyun Zhang <lzhang98@jhmi.edu>, Ding Ding <dding6@jhu.edu>
or open an issue at Github.
