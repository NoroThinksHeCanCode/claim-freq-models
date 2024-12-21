# Claim Frequency Modeling: GLMs and GAMs

This repository contains a Jupyter Notebook project focused on modeling claim frequency data using Generalized Linear Models (GLMs) and Generalized Additive Models (GAMs). The analysis leverages open-source French third-party motor liability data and is designed to reinforce concepts from the CAS MAS-I exam.

## Project Overview

### Objectives:
- Fit and compare GLMs and GAMs for modeling claim frequency.
- Explore the application of statistical techniques in actuarial science.
- Reinforce understanding of key concepts from the **CAS MAS-I** exam.

### Dataset:
- **Source**: French third-party motor liability open-source dataset.
- **Description**: The dataset contains information on motor insurance claims, including policyholder details, claim counts, and exposures.

### Key Methods:
- **Generalized Linear Models (GLMs)**: A foundational statistical approach for claim frequency modeling.
- **Generalized Additive Models (GAMs)**: An extension of GLMs that introduces flexibility with smooth functions for predictors.
- **Metrics Used**: AIC, BIC and Poisson Deviance for GLMs

## Repository Structure

- `notebooks/`
  - Contains the main Jupyter Notebook with all analyses and visualizations.
- `data/`
  - Raw and processed datasets (ensure compliance with dataset usage terms).
- `results/`
  - Outputs, including visualizations and model performance summaries.
- `README.md`
  - This file.

## Getting Started

### Prerequisites:
- Python 3.8+
- Key Libraries: `pandas`, `numpy`, `statsmodels`, `pygam`, `seaborn`, `matplotlib`, `sklearn`, `scipy`


### Usage:
Run the Jupyter Notebook to:
- Preprocess the dataset.
- Fit GLMs and GAMs to claim frequency data.
- Visualize and interpret model outputs.

## Learning Goals
This project aligns with the syllabus of the CAS MAS-I exam by demonstrating:
- Application of GLMs and GAMs in actuarial contexts.
- Techniques for working with claim frequency data.
- Insights into motor liability insurance modeling.

## Contributing
Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request.

## Acknowledgments
- CAS for providing the MAS-I syllabus and exam structure.
- Open-source French motor liability dataset contributors.
- Dobson & Barnette - An Introduction to Generalized Linear Models
- James et al. - Introduction to Statistical Learning with Python 