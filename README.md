# Analysis Code for:
# Epidemiology of Injuries and Illnesses in National Team Male Beach Soccer Players: A Prospective Seven-Year Cohort Study

## Description

# This repository contains the R code used to perform the statistical analyses and generate the figures and tables presented in the above-mentioned paper.

# Due to privacy restrictions, we are unable to share the raw data for a fully reproducible analysis. 
# However, the `data/` folder includes example data with a similar structure, which can be used to run the code and understand the workflow.

## Repository Structure

# ├── data/                  # Example data files (anonymized or simulated) and osiics cl-15 classifications
# ├── code/               # R analysis scripts
# ├── results/              # outputs (figures, tables) from analysis of real data (no personal sensitive data)
# ├── results/example          # outputs (figures, tables) from analysis of example data 
# ├── README.md              # This file

## Requirements

# To run the analysis, you will need:

# - R version ≥ 4.2.0
# - The following R packages:

install.packages(c(
  "tidyverse",
  "boot",
  "openslx",
  "ggrepel",
  "png",
  "grid"
))

## How to Run

# Run the main analysis script using R:

source("code/full_descriptive_analysis.R")

# Make sure the example data is located in the `data/` folder and matches the expected structure.

## Example Data

# The `data/` folder contains example data files that mimic the structure of the original dataset. 
# These are provided for demonstration purposes only and do not reflect real player data.

##  Contact

# For questions, please contact:

# Benjamin Clarsen  
# Medical Researcher – Global Player Health Surveillance  
# Email: ben.clarsen@fifa.org
