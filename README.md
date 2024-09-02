# Pymaceuticals Inc. - Tumor Treatment Analysis

## Overview

This project involves analyzing the efficacy of various drug regimens in reducing tumor size in a group of mice. The analysis focuses on comparing different drug regimens to determine which ones are most effective in reducing tumor volume, with particular attention to the Ramicane and Capomulin regimens.

## Key Findings

1. **Efficacy of Ramicane and Capomulin**: 
   - These regimens consistently show lower mean, median, variance, standard deviation, and standard error of the mean (SEM) in tumor volumes compared to other treatments.
   - This suggests that Ramicane and Capomulin might be more effective in reducing tumor size.

2. **Timepoint Analysis**:
   - Capomulin and Ramicane have the highest frequency of observed timepoints for each mouse, indicating these regimens were used more frequently and possibly had a significant impact on the study results.

3. **Correlation Between Mouse Weight and Tumor Volume**:
   - A strong correlation (0.84) was found between mouse weight and average tumor volume for the Capomulin regimen, suggesting a relationship between the two variables that could inform treatment effectiveness.

## Dataset Description

The dataset includes the following information:
- **Mouse ID**: Unique identifier for each mouse.
- **Drug Regimen**: The treatment administered.
- **Sex**: Gender of the mouse.
- **Age (months)**: Age of the mouse.
- **Weight (g)**: Weight of the mouse in grams.
- **Timepoint**: The time point at which data was collected.
- **Tumor Volume (mm³)**: Volume of the tumor measured in cubic millimeters.
- **Metastatic Sites**: Number of metastatic sites observed.

## Analysis Steps

1. **Data Cleaning**:
   - Handling duplicate entries for mouse IDs to ensure accurate analysis.

2. **Descriptive Statistics**:
   - Calculating summary statistics such as mean, median, and variance for tumor volumes across different regimens.

3. **Visualization**:
   - Generating plots to visualize tumor size distribution across regimens and time points.

4. **Correlation Analysis**:
   - Examining the relationship between mouse weight and tumor volume to understand the impact of the drug regimen.

## Getting Started

To run the analysis:
1. Load the dataset into a Pandas DataFrame.
2. Follow the provided code to clean the data and perform the analysis.
3. Generate visualizations and interpret the findings.

## Dependencies

- Python 3.x
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn

## Conclusion

The analysis provides insights into the effectiveness of various drug regimens in treating tumors in mice. The findings suggest that Ramicane and Capomulin are promising candidates for further investigation due to their consistent performance in reducing tumor volumes.

## Author

Hao Nguyen
