# Exploring cellular changes in ruptured human quadriceps tendons at single-cell resolution
Jolet Y. Mimpen, Mathew J. Baldwin, Claudia Paul, Lorenzo Ramos-Mucci, Alina Kurjan, Carla J. Cohen, Shreeya Sharma, Marie S.N. Chevalier Florquin, Philippa A. Hulley, John McMaster, Andrew Titchener, Alexander Martin, Matthew L. Costa, Stephen E. Gwilym, Adam P. Cribbs,
Sarah J.B. Snelling  
  
https://doi.org/10.1101/2024.09.06.611599

The full dataset can be explored on Cellxgene and downloaded from the HCA data portal  
TO DO Add links once live  

Code by [Jolet Mimpen](https://orcid.org/0000-0003-4464-242X) and [Carla Cohen](https://github.com/carlacohen)

The following scripts were used to analyse single nucleus RNA-seq data from human healthy and ruptured quadriceps tendon.  


|  | Script | Purpose |
| ----- | ------ | ------- |
| 1 | QC-filter-quadriceps.Rmd | Initial QC and filtering on a per sample basis |
| 2 | Ambient-doublet-quadriceps.Rmd | Calculate decontX score and doublet score, filter out cells with high decontX score |
| 3 | SoupX | Detect ambient RNA using SoupX with manual setting |
| 4 | Quads_1_merge_int_cluster_annotate.Rmd | Merge, integrate, cluster, annotate |
| 5 | Pseudobulk_DE_Quads_overall.Rmd | Pseudobulk (overall) |
| 6 | Pseudobulk_DE_Quads_percelltype.Rmd | Pseudobulk (per cell type) |
| 7 | 20240416_quads_fibroblasts.Rmd |Fibroblasts: integrate, cluster, annotate (Figure 3D-F, H)  |
| 8 | 20240408_quads_endothelial.Rmd |Endothelial: integrate, cluster, annotate (Figure 4A-C, F)  |
| 9 | 20240417_quads_immune.Rmd | Immune: integrate, cluster, annotate (Figure 5) |
| 10 | 20240523_quads_overwrite_cellnames.Rmd | Rename clusters with finer annotation (Suppl Fig 10, Fig 6) |
| 11 | 20240530_Quads_SCPubr.Rmd | SCPubr Progeny and TF analysis (Figure 6B)|
| 12 | 20240530_liana_ligandreceptorinteractions_detailedannotation.Rmd | Liana (Figure 6A)|
| 13 | Quads_pro-angiogenicmarkers.Rmd |Plot pro-angiogenic markers (Supplementary Figures)) |
| 14 | MiloR_Cell_Proportions-Quadriceps_JYM12Apr2024.Rmd |MiloR: all cells (Figure 1D, Supplementary Figure 7)) |
| 15 | MiloR_Cell_Proportions-fibroblasts-Quadriceps.Rmd |MiloR: fibroblasts (Figure 3G)|
| 16 | MiloR_Cell_Proportions-endothelial-Quadriceps_JYM15Apr2024.Rmd |MiloR: endothelial (Figure 4D-E) |
| 17 | MiloR_Cell_Proportions-immune-Quadriceps.Rmd |MiloR: immune (was not included) |

