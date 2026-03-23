# Comorbidity Network Analysis

This repository contains a comorbidity network analysis based on a broader research framework originally implemented in MATLAB. It focuses on one main part of that framework: constructing and analyzing a disease association network in Python. The project was done to practice network analysis methods and to better understand how a research-based study can be structured.

## Motivation

The goal of this project is to understand how diseases are connected in a comorbidity network.

## Methods

To study this, only statistically important and strong disease associations are kept. After that, a directed weighted network is built and used to analyze which diseases are more central and whether disease groups appear. To detect disease groups, the network was then converted into an undirected graph, and the Louvain algorithm was used to identify communities.

## Interpretation

Finally, the results are interpreted in terms of disease relationships, important diseases, and possible groups in the comorbidity structure.

## Data
The analysis uses two precomputed matrices from the source dataset:
- `beta1` / log-odds values from logistic regression
- p-values of statistical significance
These matrices are used as input for the network construction and analysis.
Source dataset: https://github.com/aaronab/comorbidity_networks

## Methodology

<img width="1024" height="1365" alt="methodology" src="https://github.com/user-attachments/assets/0e7805ca-241e-4693-ae82-2ccc460d7226" />


## Files
- `SNA_Analysis.ipynb`
- `README.md`

## Limitation
Because this project uses only the publicly available matrix data, it is limited to a descriptive analysis of the network structure.

  
