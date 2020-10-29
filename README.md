# BioC Owl: Learning about Bioconductor Objects

This is a 

## Learning SummarizedExperiment

The `SummarizedExperiment` class is one of the fundamental 


### Learning Objectives

**Learn** about the components of a `SummarizedExperiment` object and how they work together
**Extract** experimental information about a `SummarizedExperiment` object using `metadata()`
**Learn** and **Utilize** sample information about the experimental design of a `SummarizedExperiment` using `colData()`
**Learn**
**Construct** complex subsetting queries using `colData()` (selecting samples based on experimental design) and `rowData()` (selecting reads within a Genomic range using `subsetByOverlap()`)


### Installing

```
install.packages("remotes")
remotes::install_github("laderast/biocowl")

```

### Run the Tutorial

```
library(biocowl)
learn_summarized_experiment()
```
