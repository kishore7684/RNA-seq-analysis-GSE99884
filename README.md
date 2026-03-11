# RNA-seq Analysis of GEO Dataset GSE99884

## Overview

This project performs RNA-seq differential gene expression analysis using publicly available data from the NCBI Gene Expression Omnibus (GEO).

## Dataset

GEO Accession: GSE99884

Dataset Link:
https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE99884

## Project Structure

data/
raw → raw RNA-seq counts
processed → cleaned datasets

notebooks/
Jupyter notebooks for analysis

scripts/
Python scripts for preprocessing

results/
Differential expression results

figures/
Plots and visualizations

## Tools Used

Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook

## Analysis Workflow

GEO Dataset (GSE99884)

↓

Raw RNA-seq Count Matrix

↓

Data Preprocessing (Filtering + Normalization)

↓

Differential Gene Expression Analysis

↓

Visualization (PCA, Heatmap, Volcano Plot)

↓

Biological Interpretation



## Reproducibility

Clone the repository

git clone https://github.com/kishore7684/RNA-seq-analysis-GSE99884.git

Install dependencies

pip install -r requirements.txt

Run the analysis notebook

notebooks/RNA-seq analysis project.ipynb
