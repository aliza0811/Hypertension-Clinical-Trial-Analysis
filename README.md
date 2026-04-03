# Analysis of Hypertension Clinical Trials in India
This project analyses hypertension related clinical trial data conducted in India to identify trends in trial actiivity, study phases, sponsor participation, study types, enrollment distribution and missing data patterns. 
This project demonstrates practical data analysis workflow from raw clinical trial data to exploratory insights using Python.
## Objectives
The main objective of this project is to:
1. Clean raw clinical trial data
2. Remove unnecessary variables
3. Handle missing values
4. Standardize sponsor names
5. Perform Exploratory Data Analysis
6. Generate interpretable vizualization
## Dataset 
The dataset contains hypertension clinical trial records including
1. Study Phase
2. Sponsor
3. Enrollment Size
4. Study Type
5. Intervention details
6. Completion timelines
## Tools & Libraries Used
1. Python
2. Pandas
3. Matplotlib
4. Seaborn

## Data Cleaning Steps
The raw dataset was processed using the following steps:
1. Imported CSV file
2. Checked dataset shape and column structure
3. Identified missing values
4. Removed duplicate records
5. Dropped irrelevant columns
6. Removed rows with missing critical timeline fields
7. Filled missing categorical values:
Phases → Not Specified
Interventions → Not Specified
Study Design → Not Reported
8. Converted enrollment values into integer format

## Exploratory Data Analysis Performed
### 1. Trial Phase Analysis
A count plot was created to examine the distribution of clinical trial phases.
### 3. Sponsor Analysis
Sponsor names were standardized and top 20 sponsors were identified.
### 4. Enrollment Distribution
Enrollment was analyzed across study types using logarithmic scale.
### 5. Missing Value Analysis
Checked completeness of cleaned dataset before export.

## Key Insights
1. Most studies fall under Not Specified phase
2. Novartis, Pfizer, and AstraZeneca appear among major sponsors
3. Interventional studies dominate the dataset
4. Enrollment sizes vary widely across studies

## Output Files
The cleaned dataset was exported as:
Hypertension_India_cleaned.xlsx
Hypertension_India_final.xlsx

## Future Improvements
1. Add dashboard using Power BI or Tableau
2. Perform trend analysis by year
3. Compare sponsors across disease categories


