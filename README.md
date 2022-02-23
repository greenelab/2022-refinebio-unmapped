# Exploring unquantified fractions of RNA seq runs that have been analyzed by refine.bio

[refine.bio](https://www.refine.bio/) has harmonized thousands of gene expression experiments representing millions of samples sequenced from hundreds of organisms.
Using standard pre-processing pipelines, refine.bio RNA-sequencing data sets were quantified using [salmon](https://combine-lab.github.io/salmon/).
Salmon uses exact matching of k-mers to transcripts in a reference transcriptome to quickly quantify expression in sequencing data.
Salmon can write out fastq files of unquantified reads, which are akin to "unmapped" reads. 
This repository aims to analyze the unquantified fraction of RNA-seq samples analyzed by refine.bio. 

## Getting started with this repository

This repository uses conda to manage software installations. 
You can find operating system-specific instructions for installing miniconda [here](https://docs.conda.io/en/latest/miniconda.html).
 
```
conda env create --name refinebio --file environment.yml
conda activate refinebio
```
