# BioC Owl: Learning about Bioconductor Objects

This is a 

## Learning SummarizedExperiment

The `SummarizedExperiment` class is one of the fundamental 


### Learning Objectives

**Learn** about the components of a `SummarizedExperiment` object and how they work together
**Extract** experimental information about a `SummarizedExperiment` object using `metadata()`
**Learn** and **Utilize** sample information about the experimental design of a `SummarizedExperiment` using `colData()`
**Learn** and utilize genomic information in `rowData()` to select rows based on genomic coordinates
**Construct** complex subsetting queries using `colData()` (selecting samples based on experimental design) and `rowData()` (selecting reads within a Genomic range using `subsetByOverlap()`)
**Utilize** the `Deseq2` package to run differential expression analysis using a `SummarizedExperiment` and a experimental design (specified by a formula)


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
