# README
This repository contains all the data and code used for Santos-Medellin et al. "Acquisition of a complex root microbiome reshapes the transcriptional landscape of rice plants", 2021.

The `Analysis` directory holds all the intermediate files (`Data`) and R Notebooks (`Notebooks`) needed to generate all the `Figures` and `Tables` in the paper:

- `mbiome_assembly.Rmd` contains all the code to reproduce **Figure 2** and **Supplementary Figure 1**
- `mbiome_soil_diff.Rmd` contains all the code to reproduce reproduce **Figure 3** and **Supplementary Figure 2**
- `plant_deseq` contains all the code to perform the differential gene expression analyses. It generates the result tables used for downstream analyses.
- `plant_go_pfam` contains all the code to reproduce **Supplementary Figure 4**
- `plant_lrr` contains all the code to reproduce **Figure 5** and **Supplementary Figures 4 & 5**
- `plant_response` contains all the code to reproduce **Figure 4** **Supplementary Figure 3**
- `plant_soil_diff.Rmd` contains all the code to reproduce **Figure 6** and **Supplementary Figure 5 & 6**

The `General` directory holds a list of internal functions (`general_functions.R`) and gene annotation files that are used in the `Analysis` R Notebooks.
