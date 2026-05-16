CoxTEL: a method to correct misinterpretation of clinical trial results with long-term survival
================
Chih-Yuan Hsu

May 15, 2026


## Installation
Download CoxTEL_1.2.0.tar.gz and locally install it, or execute the following code:
``` r
library(devtools)
install_github("cyhsuTN/CoxTEL")
```

## Usage
``` r
library(CoxTEL)
```

### Web Version of CoxTEL
Upload a KM plot (png, jpg), then CoxTEL will be performed.
- CoxTEL shiny:
  <https://cyhsutn.shinyapps.io/CoxTEL_shiny/>

### CoxTEL Guidance (R code)
- [CoxTEL_R](CoxTEL_R.md)

## References
C.Y. Hsu, E.P.Y. Lin, Y. Shyr. (2021). Development and Evaluation of a Method to Correct Misinterpretation of Clinical Trial Results With Long-term Survival. JAMA Oncol. doi:10.1001/jamaoncol.2021.0289.

E.P.Y. Lin, C.Y. Hsu, J.F. Chiou et al. (2022). Cox Proportional Hazard Ratios Overestimate Survival Benefit of Immune Checkpoint Inhibitors (ICI): Cox-TEL Adjustment and Meta-analyses of PD-L1 Expression and ICI Survival Benefit. J Thorac Oncol. 17, 1365-1374. doi:10.1016/j.jtho.2022.08.010.

E.P.Y. Lin, C.Y. Hsu, L. Berry, P. Bunn, Y. Shyr (2022). Analysis of Cancer Survival associated with Immune Checkpoint Inhibitors after Statistical Adjustment: A Systematic Review and Meta-analyses. JAMA Network Open. 5(8):e2227211. doi:10.1001/jamanetworkopen.2022.27211.

