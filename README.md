# project_phase_one
# Project Title: Aircraft Safety Risk Analysis

## Project Overview
This project focuses on data cleaning, imputation, analysis, and visualization to generate insights for stakeholders regarding aircraft safety risks. The aim is to provide actionable recommendations for the new aviation division as the company expands into purchasing and operating airplanes.

## Business Problem
The company is interested in diversifying its portfolio by entering the aviation industry. However, there is limited knowledge about the potential risks associated with aircraft operations. The objective of this project is to identify which aircraft present the lowest risk for the company’s new business endeavor and provide insights to aid decision-making.

## The Data
The dataset used for this project is sourced from the National Transportation Safety Board (NTSB) and contains aviation accident data from 1962 to 2023. This dataset includes information about civil aviation accidents and selected incidents in the United States and international waters. The dataset was obtained from Kaggle.link to the dataset:https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses

### Data Folder Structure
- *data/*
  - aviation_accident_data.csv

## Key Points
- The analysis will address missing values, data aggregation, and visualization techniques to support data-driven decision-making.
- The final deliverable will include three concrete business recommendations based on the findings from the data analysis.
- Emphasis will be placed on effectively communicating the results and insights to stakeholders, particularly the head of the aviation division.

## Methodology
1. *Data Cleaning*
   - Columns with more than 50% of missing values were dropped. Others were filled with the appropriate mean, mode, and median. Only columns relevant to the analysis were considered. These included: Event Date Country, Injury Severity, Location, Aircraft Damage, Make, Model, Amateur Built, Number of Engines, Engine Type, Purpose of Flight, Total Fatal Injuries, Total Uninjured, Weather Condition, and Broad Phase of Flight.

   - Any transformations applied to the dataset.
Injury Severity: Filled missing values with the most frequent value (mode).
Location: Removed rows where the 'Location' field had missing values.
Country: Removed rows where the 'Country' field had missing values.
Aircraft Damage: Removed rows where the 'Aircraft Damage' field had missing values.
Engine Type: Removed rows where the 'Engine Type' field had missing values.
Broad Phase of Flight: Filled missing values with the most frequent value (mode).
Total Fatal Injuries: Filled missing values with the most frequent value (mode).
Remaining Missing Values: Removed any rows that still contained missing values after the previous operations.
Final Dataset Shape: Checked the number of rows and columns in the final cleaned dataset.

2. *Data Analysis*
   Pandas was used to analyze the data
   Key metrics calculated included locations of accidents, distribution of accidents over the years, aircraft category most prone to accident, the aircraft make, model, and purpose of flight, and the effect of weather.

3. *Data Visualization*
   The following plots were obtained:
   
   - Tools used for visualization (e.g., Tableau, Matplotlib).

## Recommendations
1. *Recommendation 1*: Description of the first actionable insight based on the analysis.
2. *Recommendation 2*: Description of the second actionable insight based on the analysis.
3. *Recommendation 3*: Description of the third actionable insight based on the analysis.

## Conclusion
- Summary of the project’s findings and their implications for the company's aviation strategy.
- Importance of data-driven decision-making in entering the aviation industry.

## Contact Information
- *Author*: Your Name
- *Email*: Your Email Address
- *LinkedIn*: [Your LinkedIn Profile](Your LinkedIn URL)
