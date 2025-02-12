Overview:
1. **Project's Title:**
   "Farm dust extracts as a novel therapeutic tool against asthma"
   
2. **Project Description:**
   This project compares gene expression profiles in immune and epithelial cells in different mice - subjected to three treatments.
We assess the development of allergic asthma and assess the responses of different cell-types to different treatment.

3. **Required R libraries:** You require Rstudio installed on your computer to run this analysis. You also need:
   
   req_pkages <- c("Seurat", "SeuratObject", "ggplot2", "tidyr", "tidyverse", "eeptools", "summarytools", "DT", "gplots", "knitr", "readxl", 
                "data.table", "ggrepel", "scales", "compareGroups", "FactoMineR", "factoextra", "RColorBrewer", "lmtest", "corrr", "cowplot", "dplyr", "gridExtra", "kableExtra", 
                "ggvenn", "plotly", "ggnewscale", "EnhancedVolcano", "ggpubr", "viridis", "scCustomize","pheatmap","DoMultiBarHeatmap", "patchwork")
lapply(req_pkages, require, character.only = TRUE)

5. **How to Use the Project:** Download the code, modify any file names and directories prior to compiling the Rmarkdown file.

6. **Manuscript:** Submitted as: Korkmaz et al. (2025).
