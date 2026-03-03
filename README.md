# NFL Quarterback Career Longevity Analysis

This repository contains data cleaning and exploratory data analysis (EDA) for an NFL quarterback survival analysis project. The work supports ongoing research on **career longevity and time-to-event outcomes** in professional football.

## Project Overview

- **Goal**: Explore how performance, demographics, and early-career metrics relate to **NFL quarterback career length**.
- **Methods**: Data cleaning, feature engineering, and exploratory analysis in **R/RMarkdown** to prepare inputs for downstream **survival models** (e.g., time to career end, 3-year retention).
- **Collaboration**: Conducted as part of a research project **under UCSB Statistics Professor [Tianyu Zhang]**.

## Repository Structure

- `code/`
  - [`00_nfl_EDA.Rmd`](code/00_nfl_EDA.Rmd): Main exploratory data analysis (EDA) notebook for NFL quarterback data.
  - [`Data_Documentation.Rmd`](code/Data_Documentation.Rmd): Detailed data dictionary, cleaning decisions, and variable definitions.
  - (Optional) [`Data_Documentation.pdf`](code/Data_Documentation.pdf): Rendered version of the data documentation.
- `data/`
  - Raw and intermediate CSVs (e.g., basic stats, career passing stats, game logs).
- `data/cleaned_data/`
  - `1_cleaned_nfl_data.csv`
  - `2_cleaned_nfl_data.csv`
  - `2_reorder_nfl_data.csv`
  - `3_cleaned_nfl_debut.csv`
  - `4_cleaned_nfl_3year.csv`
  - `5_ALL_DATA.csv`  
  These are **analysis-ready datasets** used for survival and longitudinal modeling.

## Data Documentation

For full variable descriptions, transformations, and cleaning logic, see:

- [`code/Data_Documentation.Rmd`](code/Data_Documentation.Rmd)
- (Rendered) [`code/Data_Documentation.pdf`](code/Data_Documentation.pdf), if available.

## Getting Started

1. **Clone the repo**

   git clone https://github.com/<your-username>/NFL-Data-Exploration.git
   cd NFL-Data-Exploration
   
