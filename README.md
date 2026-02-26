Applied Bioinformatics & Ecological Network Analysis
Overview

This repository implements a reproducible bioinformatics workflow for the analysis of plant–pollinator ecological interaction networks using publicly available biodiversity and genetic datasets.

The pipeline integrates heterogeneous biological data, performs structured cleaning and validation, constructs bipartite ecological networks, and computes quantitative network metrics to extract biologically meaningful patterns.

The project is designed following principles of:

Reproducibility

Data integrity

Structured documentation

Scalable analytical workflows

Objectives

Integrate heterogeneous biological datasets from public repositories

Clean, standardize, and validate taxonomic and occurrence data

Construct bipartite ecological interaction networks

Compute network metrics (centrality, connectivity, species importance)

Generate interpretable and reproducible analytical outputs

Data Sources

GBIF – Species occurrence records

NCBI – Genetic and taxonomic reference data

All datasets are publicly available and properly cited.

Methodology

Data acquisition and filtering

Taxonomic validation and standardization

Interaction matrix construction

Bipartite network modeling using NetworkX

Computation of ecological network metrics

Comparative and temporal analysis

Technologies & Tools

Python (pandas, numpy, networkx, matplotlib)

Jupyter Notebook

Git for version control

Reproducibility

To reproduce the analysis:
