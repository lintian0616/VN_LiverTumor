The R script file and to generate **Fig. 6**.

The R data file of pan-cancer endothelial cell RNA-seq is available from [Yin Lab](http://resource.yin-lab.com/Panvascular/Vascular_EC.jsp).


The RNA-immune infiltration data can be downloaded from [NCI's Genomic Data Commons](https://gdc.cancer.gov/about-data/publications/panimmune).

* RNA: `EBPlusPlusAdjustPANCAN_IlluminaHiSeq_RNASeqV2.geneExp.tsv`
* immune: `TCGA_all_leuk_estimate.masked.20170107.tsv`

Files         |  Description    |
--------------------|------------------|
panVEC.Rmd | R script file for scRNA-seq data of pan-cancer ECs|
TCGA_Survival.Rmd | R script file for survival analysis of TCGA data |
TCGA_Immune.Rmd  | R script file for immune infiltration analysis of TCGA data |