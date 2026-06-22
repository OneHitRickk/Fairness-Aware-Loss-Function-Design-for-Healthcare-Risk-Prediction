# Fairness-Aware Loss Function Design for Healthcare Risk Prediction

Code repository accompanying the paper submitted to AIES 2026 
(AAAI Conference on AI, Ethics, and Society).

## Overview
This repository contains five Jupyter notebooks implementing a 
fairness-aware loss function study across public clinical and 
non-clinical datasets. The core contribution is a pre-training 
diagnostic framework using Base Rate Disparity (BRD) and Positive 
Class Sparsity (PCS) to predict whether fairness regularization 
will produce a viable operating region, fail, or be unnecessary — 
before any model training begins.

## Notebooks
| Notebook | Dataset | Outcome Type |
|---|---|---|
| Heart_Disease_4F90.ipynb | UCI Heart Disease (Cleveland) | Viable |
| Adult_Income_4F90.ipynb | UCI Adult Income | Fails |
| German_Credit_4F90.ipynb | UCI German Credit | Mixed |
| Diabetes_4F90.ipynb | Diabetes 130-US | Unnecessary |
| Stroke_4F90.ipynb | Stroke Prediction | Unnecessary |

## Report
`COSC4F90_Thesis_Report.pdf` contains the full extended thesis 
report with mathematical derivations, complete results tables, 
and cross-dataset analysis.

## Authors
Rishi Modi, Brock University
Supervised by Dr. Blessing Ogbuokiri, RAML Lab
