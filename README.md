# Lombardy Neonatal Screening Dataset 

This repository contains the analysis code, supplementary files, and aggregated data associated with the Data Descriptor:

> **Extended Lombardy’s Neonatal Screening Dataset**, *Scientific Data* (2025),  
> DOI: [10.1038/s41597-025-06389-4](https://doi.org/10.1038/s41597-025-06389-4)

The curated dataset described in the article is archived on Zenodo:

> Dataset DOI: [10.5281/zenodo.16411149](https://doi.org/10.5281/zenodo.16411149)

This GitHub repository provides the computational workflow that was used to generate the tables, figures, and supplementary material reported in the manuscript.

## Background and clinical context

Since the 1960s, Neonatal Screening has been a mandatory prevention program aimed at detecting rare genetic disorders in newborns. These disorders, if left undiagnosed, can lead to significant morbidity or even mortality. In contrast, early diagnosis allows treatment to begin before symptoms appear, giving the child the opportunity to live a healthy life.

The Neonatal Screening program in the Lombardy Region targets four groups of conditions: endocrine disorders (such as congenital hypothyroidism and congenital adrenal hyperplasia), cystic fibrosis, inherited metabolic disorders (NBS), and genetic neuromuscular diseases (such as spinal muscular atrophy).

This prevention program generates a large amount of data, which is rarely shared. Over the past year, in collaboration with Dr. Luisella Alberti and Dr. Cristina Cereda, we have worked to make part of the data collected in the Lombardy Region publicly available.


## Repository contents

- `Re_SCP.ipynb`  
  Jupyter notebook containing analyses and code used to derive selected results reported in the manuscript (e.g., summary statistics, plots, tabulations).  
  The exact scope is documented in the notebook’s markdown cells.

- `Figures & Tables/`  
  Directory containing the final figures and tables (e.g., as image or PDF files) produced for the article and supplementary materials.

- `Supplementary Information/`  
  Directory with additional material not included in the main text (extended tables, additional plots, methodological details, etc.), corresponding to the Supplementary Information cited in the article.

- `.gitignore`  
  Standard Git configuration file specifying which local files and folders should not be tracked by version control.

Additional files and subdirectories may be added over time to document further analyses or updated versions of the supplementary material.


For any questions please contact g.lopiano1@campus.unimib.it
