# Gene Expression Analysis & Computational Modeling Using R

## Project Overview

This project aims to build an integrated system of functions that translates biological processes into Computer Science concepts using R.

It is designed to help Computer Science students understand biological systems through computational models, Boolean logic, data analysis, and visualization techniques.

## 1. Data Cleaning and Preprocessing

A major part of this project focuses on exploring and preparing gene expression data for further analysis.

The data preprocessing workflow includes:

- **Data Exploration:** Examining the dataset structure, dimensions, and contents.
- **Data Type Conversion:** Converting dataset values into numeric formats for statistical operations.
- **Missing Values Detection:** Identifying missing values and calculating their total count and percentage.
- **Variance Analysis:** Calculating row-wise variance to identify zero-variance or undefined-variance rows.
- **Data Filtering:** Removing rows identified as having zero or undefined variance.
- **Missing Values Visualization:** Creating a histogram to visualize the calculated missing-value percentage.
- **KNN Imputation:** Applying K-Nearest Neighbors (KNN) imputation using the `impute` package to estimate missing numerical values.

## 2. Data Transformation and Visualization

The project demonstrates data transformation and visualization techniques using R and ggplot2.

- Applying Log2 transformation with a pseudocount of 1 to sample count values.
- Creating density plots to compare raw counts and Log2-transformed counts.
- Visualizing the immune response using line plots and scatter plots.
- Using different colors to represent biological states.
- Adding horizontal and vertical reference lines to illustrate response thresholds.

### Visualizations

The project includes:
- Histogram for missing-value percentage.
- Density plot for raw counts.
- Density plot for Log2-transformed counts.
- Immune response visualization showing the relationship between antigen scores and response strength.

## 3. Computational Modeling of Biological Processes

### A. Gene Regulation Using Boolean Logic

Gene Regulatory Networks (GRNs) are modeled using Boolean logic.

- Genes are represented as binary variables (ON/OFF).
- Gene interactions are represented using logical operations.
- Activation and repression mechanisms are simulated through conditional statements.
- The function provides biological explanations alongside computational interpretations.

### B. Immune System Simulation Using Linear Scaling

The immune system is represented through a linear scaling model that simulates continuous immune responses.

- Antigen scores are mapped to response strength values between 0 and 1.
- Predefined thresholds classify biological states into:
  - SELF
  - NON-SELF
  - UNCERTAIN
- The model demonstrates how biological inputs can be translated into computational outputs.

## 4. Project Objectives

- Connect biological processes with Computer Science concepts.
- Apply data cleaning and preprocessing techniques to gene expression data.
- Explore missing-value handling using KNN imputation.
- Understand gene regulation through Boolean logic.
- Simulate immune responses using linear scaling.
- Apply data visualization techniques using ggplot2.

## 5. Technologies and Libraries

- R Programming
- Google Colab
- ggplot2
- dplyr
- Bioconductor
- impute
- patchwork

## 6. Project Files

- `R_course_gradProject.ipynb`: Main project notebook.
- `dataset2.csv`: Dataset used in the analysis.

## 7. Potential Applications

- **Bioinformatics Education:** Helping Computer Science students understand biological concepts through programming.
- **Data Analysis:** Demonstrating data cleaning, missing-value handling, and visualization techniques.
- **Computational Biology:** Exploring simplified computational representations of biological mechanisms.

## Author

**Rama Zayed**
