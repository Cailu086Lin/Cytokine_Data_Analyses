Analysis provided in the "Steroid Affected Cytokines in Aspirin Exacerbated Respiratory Disease" manuscript

This repository is meant to provide the source code for the analysis provided in the above manuscript by Li Hui Tan PhD, Cailu Lin PhD, Heather Ungerer BA, Ankur Kumar BA, Anas Qatanani BA, Nithin D Adappa MD, James N Palmer, John V Bosso MD, Danielle Reed PhD, Noam A Cohen MD PhD, Michael A Kohanski MD PhD

Abstract

Background: Patients with aspirin exacerbated respiratory disease (AERD) are among the most challenging rhinologic patients to treat. AERD has a complex inflammatory milieu of lipid mediators and cytokines. In this study we evaluated cytokine differences in the complex AERD environment at the mucus, epithelial and tissue levels.
Methods: Samples were acquired at the time of sinus surgery from twenty-one patients (7 steroid-treated, 14 untreated) with aspirin challenge-confirmed AERD. Three methods (sponge adsorption, epithelial brushing, tissue biopsy) were used to acquire samples from the respective sinus sampling sites (mucus, polyp epithelium, and full thickness polyp) of each patient. We measured and compared 16 cytokine concentrations in AERD patients with or without prednisone treatment using the Luminex platform.

Results: In most sampling sites, IL-5, IL-6, IL-10, IL-13, IL-33, CCL20, and TNFg were detected at higher concentrations than IFN-g, IL-1b, IL-17A, IL-4, IL-22, IL-17E/IL25 and GM-CSF. Each sampling site had a different pattern of cytokine levels and except for IL-5 and IL-25 there was no correlation among sampling methods for each cytokine tested. The most notable and significant decreases in cytokines from those treated with prednisone were observed in the epithelium for IL-5, IL-10, IL-33, and IFN-g.

Conclusions: In the epithelial samples, type 2 associated cytokines IL-5 and IL-33, the anti-inflammatory cytokine IL-10, and IFN-g were lower in AERD patients treated with prednisone. This work serves as a basis to assess therapeutic-induced mucosal cytokine responses in AERD and indicates that the site of cytokine measurement is an important consideration when assessing results.


sessionInfo()

R version 4.1.2 (2021-11-01)

Platform: x86_64-w64-mingw32/x64 (64-bit)

Running under: Windows 7 x64 (build 7601) Service Pack 1

Matrix products: default

Random number generation:
 RNG:     Mersenne-Twister 
 Normal:  Inversion 
 Sample:  Rejection 
 
attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

loaded via a namespace (and not attached):
  [1] pairwiseComparisons_3.1.6 circlize_0.4.13           plyr_1.8.6               
  [4] splines_4.1.2             gmp_0.6-2                 kSamples_1.2-9           
  [7] usethis_2.0.1             ggplot2_3.3.5             ipmisc_6.0.2             
 [10] TH.data_1.0-10            digest_0.6.28             SuppDists_1.1-9.5        
 [13] foreach_1.5.1             htmltools_0.5.2           fansi_0.5.0              
 [16] magrittr_2.0.1            memoise_2.0.0             gtsummary_1.4.2          
 [19] paletteer_1.4.0           cluster_2.1.2             doParallel_1.0.16        
 [22] tzdb_0.1.2                remotes_2.4.0             ComplexHeatmap_2.9.3     
 [25] readr_2.0.0               matrixStats_0.59.0        sandwich_3.0-1           
 [28] prettyunits_1.1.1         drlib_0.1.1               colorspace_2.0-2         
 [31] ggrepel_0.9.1             xfun_0.24                 dplyr_1.0.7              
 [34] callr_3.7.0               crayon_1.4.2              graph_1.70.0             
 [37] zeallot_0.1.0             survival_3.2-13           zoo_1.8-9                
 [40] iterators_1.0.13          glue_1.4.2                gtable_0.3.0             
 [43] emmeans_1.6.3             MatrixModels_0.5-0        GetoptLong_1.0.5         
 [46] statsExpressions_1.1.0    pkgbuild_1.2.0            Rgraphviz_2.36.0         
 [49] shape_1.4.6               Rmpfr_0.8-4               BiocGenerics_0.38.0      
 [52] scales_1.1.1              mvtnorm_1.1-2             DBI_1.1.1                
 [55] PMCMRplus_1.9.0           Rcpp_1.0.7                xtable_1.8-4             
 [58] performance_0.7.3         clue_0.3-60               tidyfst_1.0.0            
 [61] stats4_4.1.2              htmlwidgets_1.5.4         datawizard_0.2.1         
 [64] RColorBrewer_1.1-2        ellipsis_0.3.2            XML_3.99-0.7             
 [67] pkgconfig_2.0.3           reshape_0.8.8             multcompView_0.1-8       
 [70] utf8_1.2.2                tidyselect_1.1.1          rlang_0.4.11             
 [73] effectsize_0.4.5          munsell_0.5.0             tools_4.1.2              
 [76] cachem_1.0.6              cli_3.1.0                 generics_0.1.0           
 [79] pacman_0.5.1              devtools_2.4.2            evaluate_0.14            
 [82] stringr_1.4.0             fastmap_1.1.0             BWStest_0.2.2            
 [85] yaml_2.2.1                rematch2_2.1.2            processx_3.5.2           
 [88] knitr_1.34                fs_1.5.0                  purrr_0.3.4              
 [91] WRS2_1.1-3                pbapply_1.4-3             correlation_0.7.1        
 [94] compiler_4.1.2            rstudioapi_0.13           png_0.1-7                
 [97] testthat_3.0.4            ggsignif_0.6.3            gt_0.3.1                 
[100] tibble_3.1.3              broom.helpers_1.4.0       stringi_1.7.3            
[103] ps_1.6.0                  parameters_0.14.0         desc_1.4.0               
[106] lattice_0.20-45           Matrix_1.3-4              vctrs_0.3.8              
[109] pillar_1.6.2              lifecycle_1.0.0           mc2d_0.1-21              
[112] GlobalOptions_0.1.2       estimability_1.3          data.table_1.14.2        
[115] cowplot_1.1.1             insight_0.14.4            patchwork_1.1.1          
[118] R6_2.5.1                  IRanges_2.26.0            BayesFactor_0.9.12-4.2   
[121] sessioninfo_1.1.1         codetools_0.2-18          MASS_7.3-54              
[124] gtools_3.9.2              assertthat_0.2.1          pkgload_1.2.1            
[127] rprojroot_2.0.2           rjson_0.2.20              withr_2.4.2              
[130] multcomp_1.4-17           S4Vectors_0.30.0          bayestestR_0.11.5        
[133] parallel_4.1.2            hms_1.1.0                 fst_0.9.4                
[136] grid_4.1.2                tidyr_1.1.3               coda_0.19-4              
[139] rmarkdown_2.10            Cairo_1.5-12.2            GeneNetworkBuilder_1.34.0
[142] ggstatsplot_0.8.0        
