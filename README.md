[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0) 
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1464365.svg)](https://doi.org/10.5281/zenodo.1464365) 

[![lifecycle](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental) 
[![Travis CI](https://travis-ci.org/bnasr/phenocamapi.svg?branch=master)](https://travis-ci.org/bnasr/phenocamapi) 
[![Coverage status](https://codecov.io/gh/bnasr/phenocamapi/branch/master/graph/badge.svg)](https://codecov.io/gh/bnasr/phenocamapi)

[![CRAN status](http://www.r-pkg.org/badges/version-last-release/xROI)](https://cran.r-project.org/package=phenocamapi) 
[![Downloads](http://cranlogs.r-pkg.org/badges/phenocamapi?color=brightgreen)](http://www.r-pkg.org/pkg/phenocamapi) 
[![Downloads](http://cranlogs.r-pkg.org/badges/grand-total/phenocamapi?color=brightgreen)](http://www.r-pkg.org/pkg/phenocamapi) 


# Extracting PhenoCam data using phenocamapi R Package 

```{r}
knitr::opts_chunk$set(
  collapse = TRUE,
  comment = "#>"
)
```

PhenoCam time-series are extracted time-series data obtained from ROI's for a given site. 
Each site has specific metadata including but not limited to how the site is set-up and where it is located, what vegetaion type is visible from the camera, and its climate regime. Each PhenoCam may have none to several ROI's per vegetation type. 

This R package is an effort to simplify data wrangling steps and finally merge them as a single dataframe.

# Installation
`phenocamapi` can be directly installed from the [GitHub repo](https://github.com/phenocam/phenocamapi):
```{r}
# installing the package from the GitHub repo
if(!require(devtools)) install.packages('devtools')
devtools::install_github('phenocam/phenocamapi')

# loading the package
library(phenocamapi)
```


# Usage
The vignette page contains useful information on how to use the R package.
```{r}
browseVignettes('phenocamapi')
```

Detailed guides on how to use each function has been provided in the manual page of each function.


