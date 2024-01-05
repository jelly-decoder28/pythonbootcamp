# CCB Python Bootcamp ("PyCamp") 🐍
## A biannual introductory workshop to using Python for bioinformatics

Presented by the [Center for Computational Biology](ccb.berkeley.edu). Please contact `ccbadmin(at)berkeley.edu` for all questions.

--------------

## What is this?
This is a repository containing the notebooks, datasets, and visual assets for CCB's Python Bootcamp.

## Table of contents
- [Notebooks](#notebook-contents)
- [Datasets](#datasets)
- [Cheat sheets](#cheat-sheets)
- [Authorship](#authorship)
- [License](#license)

## Notebook contents
Each notebook is intended to be a lesson on a particular unit of Python. 

| Day | Content |
| ---- | ------ |
| **Day 1** (Monday) | Interacting with Google Colaboratory. Introduction to types, lists, tuples, sets, dictionaries. Indexing and slicing iterables. Built-in functions. Boolean logic and simple control flow. |
| **Day 2** (Tuesday) | Review basic data structures and methods. Writing custom functions. Introduction to external packages (`numpy`). |
| **Day 3** (Wednesday) | Review and cover more detail on arrays. Mini-projects on data cleaning, exploration, and basic visualization with the `badhealth` and `hepatocellular` datasets. |
| **Day 4** (Thursday) | Introduction to `pandas` operations: indexing, slicing, querying, filtering, merging. Exploration of the `clinvar` dataset.|
| **Day 5** (Friday) | Final mini-project: synthesizing content to analyze a subset of the [Tabula Muris Senis](https://www.nature.com/articles/s41586-020-2496-1) dataset.|

## Datasets
All datasets used in these materials are derived from publicly available data.

| Dataset | Source |
| ---- | ------ |
| `badhealth` | Originally from `Rdatasets`, downloaded [here](https://vincentarelbundock.github.io/Rdatasets/).
| `hepatocellular` | Originally from `Rdatasets`, downloaded [here](https://vincentarelbundock.github.io/Rdatasets/).
| `clinvar` | A table of variants from the [NCBI ClinVar](https://www.ncbi.nlm.nih.gov/clinvar/) database. Curated by [Andrew Sharo](https://www.andrewsharo.com/). |
| `facs`, `metadata_facs`, `metadata_droplet` | Single-cell count matrix and metadata tables from the [Tabula Muris Senis](https://www.nature.com/articles/s41586-020-2496-1) dataset. Downloaded using the [UCSC Cell Browser](https://cells.ucsc.edu/?ds=tabula-muris-senis). |

## Cheat sheets
Cheat sheets are included in each subdirectory. Credits are provided below.

| Day | Source |
| ---- | ------ |
| **Day 1** (Monday) | Custom written by [Stacy Li](stacy.li) for PyCamp. |
| **Day 2** (Tuesday) & **Day 3** (Wednesday) | DataCamp |
| **Day 4** | PyData |
| **Day 5** | DataCamp |

## Authorship
Current notebooks and curriculum were developed by [Stacy Li](stacy.li) in Summer 2022, with exercises contributed by PyCamp staff in the years following. Pre-2022 notebooks were developed by previous generations of PyCamp staff.

## License
This repository is licensed under the [CC 4.0 license](https://creativecommons.org/licenses/by/4.0/). You are free to share, redistribute, and adapt these notebooks, although we request that you provide a link to this repository.