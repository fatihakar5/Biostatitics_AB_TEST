# Biostatistics Dataset Analysis with AB Testing

This project involves analyzing a biostatistics dataset containing a DIAGNOSIS variable, coded as 0 and 1. Initially, there was no information on what these values represented, so the analysis focused on understanding the dataset, preparing the data, and then using AB testing to uncover the possible meaning of each diagnostic group.

## Project Overview

The project includes the following steps:

1. Data Loading and Preprocessing

    - The dataset was loaded and inspected.
    - The DIAGNOSIS variable was originally coded as 1 and 2, which was standardized to 0 and 1 for consistency.
    - Column names were adjusted for better readability, and an unnecessary variable was removed.

2. Exploratory Data Analysis

    - Distributions of categorical and numerical variables were explored.
    - Visualizations were created to better understand data patterns and distributions.
    - Missing and outlier values were handled to prepare a clean dataset for further analysis.

3. Dataset Splitting

    - The dataset was divided into two groups based on the DIAGNOSIS variable:
    - Group 0: Diagnosis unknown
    - Group 1: Diagnosis unknown

4. AB Testing on Diagnostic Groups

    - AB tests were applied to compare the two groups. The results indicated that Group 0 likely represents individuals with health issues, while Group 1 may represent healthier individuals.
  
5. Results
    - Through this analysis, we derived that the DIAGNOSIS variable's 0 and 1 values likely represent two distinct health-related groups within the dataset. The results suggest that the 0 group may correspond to individuals with health issues, while the 1 group may represent healthier individuals. Although the specific conditions of each group are still unidentified, this foundational analysis provides a basis for further exploration of characteristics within each group.
  
6. Project Kaggle link : [https://www.kaggle.com/code/fatihakar5/biostatistics-ab-test]
