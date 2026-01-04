# Data-Driven Optimization of Meropenem–Thyme Oil Co-Loaded Nanostructured Lipid Carriers (NLCs)

## Project Overview
This project applies data-science techniques to experimental formulation data derived from an MSc thesis on meropenem–thyme oil co-loaded nanostructured lipid carriers (NLCs) developed for respiratory infections.

Using Python-based statistical analysis and visualization, the study identifies key physicochemical drivers of formulation performance and applies multi-criteria decision analysis (MCDA) to objectively determine the optimal formulation.

---

## Dataset
The dataset includes experimentally measured formulation parameters:
- Particle size (nm)
- Polydispersity index (PDI)
- Zeta potential (mV)
- Encapsulation efficiency (%)
- Thyme oil loading (mg)

All data were extracted programmatically from the thesis document and cleaned for analysis.

---

## Methods
The analytical workflow includes:
1. Automated extraction of tables from the thesis document
2. Data cleaning and normalization
3. Correlation analysis (Pearson correlation heatmap)
4. Trade-off visualization:
   - Size vs Encapsulation Efficiency
   - PDI vs Encapsulation Efficiency
   - Zeta Potential vs PDI
5. Multi-criteria optimization scoring integrating:
   - Particle size (minimized)
   - PDI (minimized)
   - Absolute zeta potential (maximized)
   - Encapsulation efficiency (maximized)

Weights were assigned based on pharmaceutical formulation priorities.

---

## Key Findings
- Particle size showed a strong positive correlation with encapsulation efficiency.
- Lower PDI was associated with improved encapsulation efficiency.
- Zeta potential remained stable across formulations, indicating good colloidal stability.
- Batch D was identified as the optimal formulation, balancing homogeneity, stability, and high encapsulation efficiency.

---

## Repository Structure
nlc-data-projects/
├── README.md
├── data/
├── figures/
├── notebooks/
├── outputs/
├── src/
└── 01_optimization_dashboard.ipynb
---

## Tools
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- JupyterLab
- Multi-criteria decision analysis (MCDA)
- Scientific data visualization

---

## Relevance
This project demonstrates the integration of pharmaceutical formulation science with data-driven analytics and decision-making, reflecting real-world pharmaceutical R&D workflows.

---

## Author
Ali Ahmad  
MBBS | MSc Clinical & Molecular Microbiology | MSc Drug Discovery & Development  
Research interests: Nanomedicine, drug delivery, antimicrobial therapy, and data-driven pharmaceutical science
