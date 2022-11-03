# MAD1L1_syndrome_aneuploidy

## Description

This github repository contains the analysis code used in "Bilallelic germline mutations in MAD1L1 induce a syndrome of aneuploidy with high tumor susceptibility" published in Science Advances:

Link: https://www.science.org/doi/10.1126/sciadv.abq5914

## Table of contents

- [Data](#Data)
- [Scripts](#Scripts)


## Data

scRNA-seq data are available at the GEO repository under the accession code: [GSE197267](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE197267). Proteomics data are available at ProteomeXchange (Project accession: PXD035765). R and Python notebooks used in this work are accessible at [Zenodo](https://zenodo.org/record/6960105#.YweMyi8lMTs) and [malumbreslab](https://github.com/malumbreslab/MAD1L1_syndrome_aneuploidy) Github. All data needed to evaluate the conclusions in the paper are present in the paper and/or the Supplementary Materials.

## Scripts

- [Preprocessing.ipynb](/scripts/Preprocessing.ipynb): Using as input files CellRanger outputs, it is done a preprocessing in python code of single cell data from patient, father, mother control1 and control2.
- [scRNAseq.ipynb](/scripts/scRNAseq.ipynb): contains the python code to reproduce all single cell analysis (statistics, visualization, differential expression, functional analysis, aneuploidy)
- [inferCNV.ipynb](/scripts/inferCNV.ipynb): contains the python code to infer copy number variations from single cell data.
- [Interaction.ipynb](/scripts/Interaction.ipynb): contains the python code to manage interaction data from [cellphoneDB](https://github.com/Teichlab/cellphonedb).
