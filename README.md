# What the project does
This project analyses regional disparities in access to electricity and clean fuels, using data from the World Bank (2021).
The dataset covers 264 regions between 1990 and 2019, tracking both temporal and cross-regional variations in energy accessibility.

The analysis includes data overview, data wrangling, data visualisation and interpretation. The project focuses on tracking yearly changes in electricity and clean fuel access rate, as well as differences between populations with and without access within each region to highlight regional progress and development. It also focuses on comparing average access rates across regions to highlight regional disparities.

This project is important because it can inform policymakers to design more evidence-based and targeted interventions to reduce global inequality.

# How users can get started with the project
The R version needed for this project is 4.5.1 (2025-06-13).

The compressed project folder contains:
- R scripts (`.R` files)  
- Dataset (`.csv`)  
- `README.md`  
- The main report (`.html`)  
- Relevant figures and outputs
- Assignment coversheet 

To reproduce the analysis, install the following R packages:

if (!require("pacman")) {
  install.packages("pacman")
}

pacman::p_load(
  tidyverse,
  skimr,
  ggplot2,
  glue,
  kableExtra
  ) 

After loading and placing the dataset, you can run the scripts and data wrangling and visualisation functions.

# Where users can get help with your project
If you encounter issues or have questions, please email my UCL address.

# Who maintains and contributes to the project
This project is maintained by the candidate TZHM6.
