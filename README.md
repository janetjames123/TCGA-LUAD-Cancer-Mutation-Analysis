# TCGA Lung Cancer Mutation Analysis

## Overview
Somatic mutation landscape analysis of 616 lung adenocarcinoma (LUAD) 
patients using real TCGA genomic data. Identifies frequently mutated 
genes, mutation patterns and survival associations.

## Research Questions
1. What mutation types dominate lung adenocarcinoma?
2. Which genes are most frequently mutated?
3. Does KRAS mutation status affect patient survival?

## Key Findings
- TP53 mutated in 50% of patients — most frequently altered gene
- C>A mutations dominant — classic cigarette smoke DNA signature
- KRAS mutated in 26% of patients — major drug target
- KRAS mutation alone does not significantly affect survival (p = 0.71)

## Plots

### Mutation Summary Dashboard
![Mutation Summary](plots/mutation_summary.png)

### Oncoprint — Top 20 Mutated Genes
![Oncoprint](plots/oncoprint.png)

### TP53 Lollipop Plot
![TP53 Lollipop](plots/lollipop_tp53.png)

### KRAS Survival Analysis
![Survival](plots/survival_plot.png)

## Tools and Packages
- R 4.x
- TCGAbiolinks
- maftools
- ComplexHeatmap
- survival + survminer
- tidyverse

## Data Source
The Cancer Genome Atlas (TCGA) — TCGA-LUAD project
616 lung adenocarcinoma patient samples
Accessed via GDC Data Portal (open access)

## How to Run
1. Install required packages (see analysis.R)
2. Run analysis.R in RStudio sequentially
3. Plots saved to working directory

## Author
Janet James
