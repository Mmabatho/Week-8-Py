# README: COVID-19 Data Analysis Notebook

## Overview

This Jupyter Notebook analyzes the COVID-19 pandemic using the [owid-covid-data.csv](owid-covid-data.csv) dataset. The analysis covers data cleaning, exploratory data analysis, and visualization of key pandemic metrics such as total cases, deaths, and vaccination progress across different countries.

## Key Steps and Findings

### 1. Data Loading and Cleaning
- The dataset is loaded using pandas.
- Missing values are identified and handled, especially for critical columns like `date`, `iso_code`, `total_cases`, and `population`.
- Dates are converted to datetime format for accurate time-based analysis.

### 2. Exploratory Data Analysis (EDA)
- **Top Countries by Cases and Deaths:**  
  - The notebook identifies the top 10-15 countries with the highest total COVID-19 cases and deaths.
  - Line charts visualize trends in total cases and deaths over time for these countries.
- **Vaccination Progress:**  
  - Randomly selects three countries with vaccination data and plots their total vaccinations over time.
- **Smoking Rates:**  
  - For a randomly selected country with available data, a pie chart shows the proportion of male and female smokers.

### 3. Choropleth Map Visualization
- A choropleth map is created to visualize COVID-19 case density (cases per 100,000 people) by country.
- This map helps identify regions with the highest and lowest case densities.

### 4. Additional Insights
- The notebook includes code to filter and display the latest available data, as well as to identify countries with the highest case counts on the most recent date.

## How to Use

1. **Requirements:**  
   - Python 3.x  
   - Jupyter Notebook  
   - Libraries: pandas, matplotlib, seaborn, plotly, numpy

2. **Running the Notebook:**  
   - Open `covid_data.ipynb` in Jupyter Notebook or VS Code.
   - Ensure `owid-covid-data.csv` is in the same directory.
   - Run all cells sequentially to reproduce the analysis and visualizations.

## Summary of Findings

- The pandemic's impact varies significantly by country, with some countries experiencing much higher case and death counts.
- Vaccination progress also differs, with some countries achieving higher total vaccinations earlier.
- The choropleth map highlights global disparities in case density, revealing hotspots and regions with lower reported cases.
- Smoking rates by gender are visualized for a randomly selected country, providing additional demographic insight.

---

**Note:**  
This analysis is based on the data available in the provided CSV file. Results and visualizations may change as the dataset is updated.