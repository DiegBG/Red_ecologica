### Applied Bioinformatics & Ecological Network Analysis
# Overview

This repository implements a reproducible bioinformatics workflow for the analysis of plant–pollinator ecological interaction networks using publicly available biodiversity and genetic datasets.

The pipeline integrates heterogeneous biological data, performs structured cleaning and validation, constructs bipartite ecological networks, and computes quantitative network metrics to extract biologically meaningful patterns.

The project is designed following principles of:

- Reproducibility
- Data integrity
- Structured documentation
- Scalable analytical workflows

# Objectives

- Integrate heterogeneous biological datasets from public repositories

- Clean, standardize, and validate taxonomic and occurrence data

- Construct bipartite ecological interaction networks

- Compute network metrics (centrality, connectivity, species importance)

- Generate interpretable and reproducible analytical outputs

# Data Sources

- GBIF – Species occurrence records

- NCBI – Genetic and taxonomic reference data

All datasets are publicly available and properly cited.

# Methodology

1-Data acquisition and filtering

2-Taxonomic validation and standardization

3-Interaction matrix construction

4-Bipartite network modeling using NetworkX

5-Computation of ecological network metrics

6-Comparative and temporal analysis

# Technologies & Tools
- Python (pandas, numpy, networkx, matplotlib)
- Jupyter Notebook
- Git for version control

# Reproducibility

To reproduce the analysis:

git clone https://github.com/DiegBG/Red_ecologica.git
cd Red_ecologica
pip install -r requirements.txt

# Project Structure 

Red_ecologica/
│
├── data/              # Raw and processed datasets
├── notebooks/         # Jupyter notebooks for analysis
├── src/               # Modularized analysis scripts
├── results/           # Generated figures and outputs
├── requirements.txt   # Project dependencies
└── README.md

# Key Outputs
-Bipartite ecological network visualization
-Species centrality metrics
-Interaction connectivity analysis
-Comparative temporal patterns

# Author

Diego Antonio Becerril García
Applied Bioinformatics | Scientific Data Analysis | Biomedical Engineering

