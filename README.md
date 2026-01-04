# NLC Data Projects

Data-driven analysis and optimization of nanostructured lipid carriers (NLCs) for drug delivery applications.

## Project Overview
This repository contains reproducible data analysis workflows derived from an MSc thesis focused on
meropenem–thyme oil co-loaded NLCs. The goal is to apply statistical analysis and visualization to
identify optimal formulations based on physicochemical properties.

## Dataset
Extracted from experimental tables in the MSc thesis, including:
- Particle size (nm)
- Polydispersity index (PDI)
- Zeta potential (mV)
- Entrapment efficiency (%)
- Thyme oil concentration (mg)

## Analysis Included
- Data cleaning and standardization
- Correlation heatmaps of NLC parameters
- Scatter plots (Size vs EE, Zeta potential vs PDI)
- Composite optimization scoring for formulation ranking

## Key Findings
- Strong positive correlation between particle size and entrapment efficiency
- Lower PDI associated with improved formulation stability
- Batch D identified as the optimal formulation based on weighted multi-parameter scoring

## Repository Structure
data/ → Raw and extracted experimental tables
figures/ → Publication-quality plots
notebooks/ → Jupyter notebooks for analysis
outputs/ → Processed datasets
src/ → Utility scripts

## Tools Used
- Python (pandas, numpy, matplotlib, seaborn)
- JupyterLab
- Git & GitHub

## Author
**Ali Ahmad**  
MSc Drug Discovery & Development | Clinical & Molecular Microbiology  
