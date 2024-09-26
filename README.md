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
*Injury Severity: Filled missing values with the most frequent value (mode).*
*Location: Removed rows where the 'Location' field had missing values.*
*Country: Removed rows where the 'Country' field had missing values.*
*Aircraft Damage: Removed rows where the 'Aircraft Damage' field had missing values.*
*Engine Type: Removed rows where the 'Engine Type' field had missing values.*
*Broad Phase of Flight: Filled missing values with the most frequent value (mode).*
*Total Fatal Injuries: Filled missing values with the most frequent value (mode).*
*Remaining Missing Values: Removed any rows that still contained missing values after the previous operations.*
*Final Dataset Shape: Checked the number of rows and columns in the final cleaned dataset.*

2. *Data Analysis*
   Pandas was used to analyze the data
   Key metrics calculated included locations of accidents, distribution of accidents over the years, aircraft category most prone to accident, the aircraft make, model, and purpose of flight, and the effect of weather.

3. *Data Visualization*
   The following plots were obtained:
   1.![image](https://github.com/user-attachments/assets/d8b30994-e3be-4d31-a9d0-eed2aab7194c)
   2.![image](https://github.com/user-attachments/assets/8e7e1e1e-cd1c-4bef-a137-e879960b4150)
   3.![image](https://github.com/user-attachments/assets/ae47c0f0-869d-4e28-a143-d0b45141cf4c)
   4.![image](https://github.com/user-attachments/assets/cc5090a7-d7c8-4b43-a7c5-a3672d364bad)
   5.![image](https://github.com/user-attachments/assets/fdec4c04-bd55-47b9-911a-8933a595f5a5)
   6.![image](https://github.com/user-attachments/assets/6875a9ee-eabd-4d30-b6ce-e3f0cff88e53)
   7.![image](https://github.com/user-attachments/assets/46ccc7e5-8640-4b46-b6c3-28460c87ebb4)
   8.![image](https://github.com/user-attachments/assets/98a0181c-3d1b-4c13-8a69-906ba9fcde5c)
   9.![image](https://github.com/user-attachments/assets/1c7a40eb-2102-4f2d-97ad-8dffaad4af72)

Tableau ,matplotlib and  seaborn were used for the visualization.
link to the tableau:https://public.tableau.com/app/profile/stephen.otieno3229/viz/AVIATIONRISKANALYSISPROJECT/AVIATIONRISKANALYSIS

## Recommendations
1. *Recommendation 1*: It is safe to invest in the aviation industry.
2. *Recommendation 2*: Aircrafts meant for businesses are safe to invest in.
3. *Recommendation 3*: Location, weather condition, engine type, make and model contribute to the safety of an aircraft and should be considered.

## Conclusion.
 In conclusion, investing in aviation is safe due to the decline in accidents, most of which are non-fatal. Business aircraft with turbojet engines are ideal, as they have lower accident rates. Location and weather matter, so areas with poor weather should be avoided. Most accidents happen during landing and takeoff, so better pilot training and improved airport visibility can reduce accidents.
Data-driven decision-making is crucial in the aviation industry as it helps identify trends, reduce risks, and improve safety. By analyzing accident data, aircraft performance, and environmental factors, businesses can make informed choices on the best aircraft, engine types, and operating locations. This approach minimizes uncertainty, enhances operational efficiency, and supports safer investments, ultimately leading to better outcomes and competitive advantages in the industry.

## Contact Information
- *Author*: Stephen Otieno
- *Email*: stephenochieng037@gmail.com
