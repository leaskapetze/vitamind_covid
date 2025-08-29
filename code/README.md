# Monitoring Changes in Vitamin D Levels Before and During the COVID-19 Pandemic
## Overview
This project analyzes changes in vitamin D levels before and during the COVID-19 pandemic, based on real-world healthcare data. The analysis focuses on mean levels, deficiency rates, and subgroup-specific trends across age groups, gender, and seasons.

## Requirements
To ensure reproducibility, please use:
R version: 4.3.2 (or compatible)
RStudio: recommended but not mandatory

## Required R Packages
The following R packages are required (version numbers tested):
tidyverse (>= 2.0.0)
dplyr (>= 1.1.4)
ggplot2 (>= 3.4.4)
readr (>= 2.1.4)
lubridate (>= 1.9.3)
knitr (>= 1.45)
kableExtra (>= 1.4.0)
It is recommended to install the exact package versions or use an environment manager like renv to lock the environment.

## Environment Setup (Optional but Recommended)
To replicate the environment exactly, you can use the renv package:

install.packages("renv")

renv::init()

renv::snapshot()

This will create a lockfile (renv.lock) ensuring full reproducibility. You can also use the renv.lock file attached.

## Usage
1. Download the R Markdown file (Monitoring_changes_in_vitamin_D_levels_code.Rmd)
2. Prepare the data: Make sure your dataset is loaded into the df object as expected by the script.
3. Open the .Rmd file in RStudio or an R-capable IDE.
4. Knit the file to HTML, Word, or PDF to reproduce the full analysis and output.
5. Output: The final document includes descriptive analyses, subgroup-specific statistics (mean, median, IQR, standard deviation), and statistical tests (t-tests, Wilcoxon tests, chi-square tests).

If using different versions of R or packages, results may vary slightly.
