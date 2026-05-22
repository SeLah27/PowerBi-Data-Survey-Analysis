# Data Professional Survey Analysis | Power BI Dashboard

## Project Overview
Interactive Power BI dashboard analyzing responses from 630 data professionals 
across 40+ countries, uncovering patterns in compensation, job satisfaction, 
career transitions, and barriers to entry in the data field.

## Tools Used
- Power BI Desktop — data modeling, DAX measures, dashboard design
- Excel — source data preparation

## Dataset
Survey of 630 data professionals collected in 2022. Variables include job title, 
industry, salary range, programming language preference, satisfaction scores 
across 6 dimensions, and demographic data.

1. Demographics & Geographic Distribution
Country of Survey Takers: Utilizes a Treemap visualization to instantly highlight market concentration. The United States and India represent the largest blocks of respondents, alongside significant participation from the UK, Canada, and other global regions.

Gender Distribution across Jobs: A Stacked Bar Chart breakdown showing gender representation within specific titles, highlighting that Data Analyst roles currently hold the highest survey engagement.

2. Compensation & Market Trends
Average Salary by Job Title: A horizontal Bar Chart that dynamically showcases earning benchmarks. Data Scientists and Data Architects lead the salary metrics, providing clear reference data for commercial and organizational tracking.

3. Technical Preferences
Favorite Programming Language: A Stacked Column Chart segmenting language popularity by job title. Python is overwhelmingly identified as the dominant language across the board, followed by R and other general-purpose languages.

4. Industry Sentiment
Difficulty to Break into Data: A Donut Chart visualization assessing market accessibility. Over 42% of respondents view entering the data field as "Neither easy nor difficult," while a combined approx. 31% classify it as "Difficult" or "Very Difficult."

🏗️ Data Governance & Quality Standards
To ensure strict data integrity before building the visuals, the following data management protocols were implemented via Power Query:

Schema Design: Established strict field categories and relational dependencies to prevent data redundancy.

Data Cleansing: Formatted inconsistent naming conventions within the "Job Title" and "Country" fields to establish a clean reference data baseline.

Granularity Maintenance: Filtered out outliers and blank responses from the salary fields to avoid skewed averages in data visualizations.
