# Exploratory Factor Analysis of Global Education Indicators

## Overview

This project analyzes global education indicators across countries using statistical modeling and exploratory data analysis techniques in R. The goal of the project was to investigate how educational outcomes differ between countries and identify social, economic, and infrastructure-related factors that may influence education systems worldwide.

The project combines multiple international datasets related to:
- Expected years of schooling
- Mean years of schooling
- Government education spending
- Human rights indicators
- School water accessibility
- Population density
- Research publication metrics

Using these datasets, we performed data cleaning, exploratory data analysis (EDA), factor analysis, and structural equation modeling (SEM) to identify relationships between educational infrastructure, human development, and national investment in education.

---

## Research Questions

Some of the main questions explored in this project include:

- What factors are most associated with strong educational outcomes?
- How do infrastructure and human rights relate to education?
- Does population density influence educational investment?
- Are there hidden latent variables that explain differences between countries?

---

## Technologies Used

- R
- RMarkdown
- ggplot2
- dplyr
- psych
- lavaan
- corrplot
- GGally

---

## Data Sources

The datasets used in this project were collected from:
- Our World in Data
- International education datasets
- Population and publication datasets

The project merged multiple datasets together by country in order to perform cross-country analysis.

---

## Methods and Analysis

The project included several stages of analysis:

### Data Cleaning and Preparation
- Merging multiple datasets
- Handling missing values
- Renaming and organizing variables
- Preparing numerical matrices for analysis

### Exploratory Data Analysis
- Descriptive statistics
- Correlation analysis
- Pairwise plots
- Distribution visualizations

### Outlier Detection
- Mahalanobis distance analysis
- Country-level outlier interpretation

### Exploratory Factor Analysis (EFA)
- Eigenvalue analysis
- Scree plots
- Orthogonal and oblique rotations
- Factor interpretation

### Structural Equation Modeling (SEM)
- Latent variable modeling
- Path analysis
- Model fit evaluation
- Predictor significance testing

---

## Key Findings

Some major findings from the analysis included:

- Educational infrastructure, particularly school water access, was strongly associated with human development indicators.
- Countries with better school infrastructure tended to invest a larger share of GDP into education.
- Population density showed a negative relationship with education spending in some cases.
- Multiple latent factors explained variation in education outcomes across countries.

The project also demonstrated that global education systems are influenced by interconnected economic, demographic, and infrastructure-related variables.

---

## Running the Project

### Requirements

Install the required R packages:

```r
install.packages(c(
  "tidyverse",
  "dplyr",
  "jsonlite",
  "readxl",
  "psych",
  "ggplot2",
  "corrplot",
  "GGally",
  "lavaan",
  "parameters"
))
```

### Running the Analysis

1. Open the `.Rmd` file in RStudio
2. Install required packages
3. Run the RMarkdown file
4. Knit the document to generate the final HTML report

---

## Files Included

- `Project_DATA.Rmd` — Main analysis and code
- `Project_DATA.html` — Generated report
- `world_population.csv` — Population dataset
- `publications.xlsx` — Publication/citation dataset
- `PS Path.drawio.png` — SEM path diagram

---

### Connection to the Common Good

This project connects to the common good by analyzing global education data to better understand the factors that influence educational opportunities and human development across countries. The analysis highlights how infrastructure, human rights, and public investment can affect access to education, helping promote awareness of global inequality and educational development.

---

## My Contributions

My contributions to this project included:
- Data cleaning and preprocessing
- Exploratory data analysis
- Statistical interpretation
- Visualization development
- Factor analysis interpretation
- Report writing and documentation

---

## Team Information

This project was completed as a collaborative data science project at the University of St. Thomas.
