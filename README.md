# DataUsage_Survey_Analysis

This repository contains R code used for data analysis of the survey data generated for the Probst, Hug, Hatzenpichler, Moraru, Soares, Heyder & Meyer (2024) manuscript.

File list & description:

 - NCBI_SRA_overtime: Analyis of available SRA data and model fitting to extrapolate data numbers by 2030 - **Figure S1** of the manuscript (RMarkdown and HTML)
 - response_analysis_090224: Analysis of survey data - **Figures S2-10** and **Tables S1-4**

R environment used to run both RMD files:
```
> sessionInfo()
R version 4.3.1 (2023-06-16)
Platform: aarch64-apple-darwin20 (64-bit)
Running under: macOS Sonoma 14.1.2

Matrix products: default
BLAS:   /System/Library/Frameworks/Accelerate.framework/Versions/A/Frameworks/vecLib.framework/Versions/A/libBLAS.dylib 
LAPACK: /Library/Frameworks/R.framework/Versions/4.3-arm64/Resources/lib/libRlapack.dylib;  LAPACK version 3.11.0

locale:
[1] en_US.UTF-8/en_US.UTF-8/en_US.UTF-8/C/en_US.UTF-8/en_US.UTF-8

time zone: Europe/Berlin
tzcode source: internal

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
 [1] patchwork_1.1.3    kableExtra_1.3.4   ggsankey_0.0.99999 lubridate_1.9.3   
 [5] forcats_1.0.0      stringr_1.5.1      dplyr_1.1.4        purrr_1.0.2       
 [9] readr_2.1.4        tidyr_1.3.1        tibble_3.2.1       ggplot2_3.4.4     
[13] tidyverse_2.0.0   

loaded via a namespace (and not attached):
 [1] utf8_1.2.4        generics_0.1.3    xml2_1.3.6        stringi_1.8.3    
 [5] hms_1.1.3         digest_0.6.33     magrittr_2.0.3    evaluate_0.23    
 [9] grid_4.3.1        timechange_0.2.0  fastmap_1.1.1     jsonlite_1.8.8   
[13] processx_3.8.3    chromote_0.1.2    ps_1.7.5          promises_1.2.1   
[17] httr_1.4.7        rvest_1.0.4       fansi_1.0.6       viridisLite_0.4.2
[21] scales_1.3.0      cli_3.6.2         rlang_1.1.3       munsell_0.5.0    
[25] withr_3.0.0       yaml_2.3.8        tools_4.3.1       tzdb_0.4.0       
[29] colorspace_2.1-0  webshot_0.5.5     vctrs_0.6.5       R6_2.5.1         
[33] lifecycle_1.0.4   pkgconfig_2.0.3   pillar_1.9.0      later_1.3.2      
[37] gtable_0.3.4      glue_1.7.0        Rcpp_1.0.11       systemfonts_1.0.5
[41] xfun_0.41         tidyselect_1.2.0  rstudioapi_0.15.0 knitr_1.45       
[45] websocket_1.4.1   htmltools_0.5.7   svglite_2.1.3     rmarkdown_2.25   
[49] compiler_4.3.1
```
