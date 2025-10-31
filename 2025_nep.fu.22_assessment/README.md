# 2025_nep.fu.22_assessment
2025 - Norway lobster (Nephrops norvegicus) in divisions 7.f and 7.g, Functional Unit 22 (Celtic Sea, Bristol Channel) - WGNEPH (ADGNEPH)



## R packages 

## Mixfish object Output available:
output_01_assessment_summary.html/rmd
section 2.2_Reformat_for_WGMIXFISH_Stock_object
fu22.nep.stock.wgmixfish.csv


The following R packages from CRAN are required to run the assessment:

```
library(RODBC)
library(tidyverse)
library(lattice)
library(lubridate)
library(mapplots)
library(sp)
library(sf)
library(reshape2)
library(readxl)
library(knitr)
library(DataCombine)
library(lattice)
library(icesTAF)
library(magrittr)
library(viridis)
library(sessioninfo)
library(stringr)
library(RColorBrewer) 


library(fields)
library(gstlearn)
library(maps)
library(mapproj)
.Last.projection=list(active=F,projection="mean",parameters=NULL,orientation=NULL)
```