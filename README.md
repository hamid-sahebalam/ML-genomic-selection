# ML-genomic-selectin
R scripts for genomic prediction using machine learning and parametric methods 
# ML-simulation

This repository contains R scripts used in the manuscript:

"Feed-Forward Neural Networks for Genomic Selection: Insights into Varying levels of Dominance Heritability"

## Description
The provided R script implements the full simulation and genomic prediction pipeline for the purely additive genetic architecture, including:

- Genotype simulation
- Phenotype generation
- Genomic prediction using:
  - GBLUP
  - BayesB
  - BayesL
  - Random Forest (RF)
  - Support Vector Machine (SVM)
  - Feed-Forward Neural Network (FFNN)

This additive scenario represents the general simulation framework used throughout the study. Other additive scenarios differ only in the specification of additive heritability parameter.
Other scenarios, including those with dominance effects, follow the same pipeline but extend the genomic inputs to include additive and dominance genomic relationship matrices. 
Scripts for these dominance scenarios are available upon request.
## Software
- R version: 4.5.1
- Main packages:
  - xbreed
  - BGLR
  - randomForest
  - e1071
  - brnn

## Author
Hamid Sahebalam
