---
lastmod: "2019-12-21T12:49:01Z"
publishdate: "2019-12-21"
draft: no
title: Initial Setup
weight: 20
---

### Sample Data

The sample dataset used in the vignettes is from publication by [Gaydosik AM *et al*](https://www.ncbi.nlm.nih.gov/pubmed/31010835). It can be downloaded from [here](https://github.com/xmc811/Scillus/blob/development/test/GSE128531.tar.gz). Once downloaded, the file can be unzipped by `tar xvzf GSE128531.tar.gz`. There is no need to further unzip the individual `.csv.gz` files. To reduce computation time, the dataset only includes 6 samples and 300 cells for each sample. The complete raw data are available at [GEO](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE128531).

The sample data are in `.csv.gz` format, but Scillus also works for 10xGenomics cellranger output format like below:

```console
$ tree filtered_feature_bc_matrix
filtered_feature_bc_matrix
├── barcodes.tsv.gz
├── features.tsv.gz
└── matrix.mtx.gz
```

### Metadata

The sample sizes for each scRNA-seq project are almost always more than one. Hence, the loading and filtering functions of Scillus will generate and process a list of Seurat objects.

### Palette setup

The plotting functions of Scillus will incorperate palette setup to ensure consistent coloring schemes for each variable in different types of plots.