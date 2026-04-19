# BERTIDF-CNN Resume & FairCVdb Benchmarks

This repository provides reproducibility-oriented notebooks for resume classification and external validation with FairCVdb.

## Repository structure

- `notebooks/01_resume_benchmark_and_article_tables.ipynb`: resume benchmark, article-style tables, curves, and confusion matrices.
- `notebooks/02_faircvdb_benchmark_and_article_tables.ipynb`: FairCVdb benchmark.
- `data/Resume.csv`: resume dataset used by the notebooks.
- `data/faircvdb.npy`: FairCVdb dataset file.
- `figures/`: optional folder for saved plots and exported visualizations.

## Recommended paths in Google Colab

The notebooks are designed to work with Google Drive paths such as:

- `/content/drive/MyDrive/MLDL-NLP/DATASETS/CV/Resume.csv`
- `/content/drive/MyDrive/MLDL-NLP/DATASETS/CV/faircvdb.npy`


## Scope

The current version focuses on:

- benchmarking classical, recurrent, transformer, and hybrid models
- emphasizing BERTIDF-CNN as the proposed model
- producing article-oriented tables
- plotting training curves and confusion matrices

