# Tableau - BigQuery

## Overview
"Finding Name" is a Tableau-based analysis exploring the influence of time and location on naming trends in the USA. Utilizing data from Google BigQuery USA Names, this project investigates the patterns in the popularity of male names across different generations and states.

## Files
- `finding_name.twb`: The Tableau workbook file with the analysis.

## Getting Started
To use this workbook:
- Ensure you have Tableau Desktop installed.
- Download the .twb file from this repository.
- Open the file using Tableau Desktop.

## Data
The analysis uses the Google BigQuery USA Names dataset, focusing on male names across various US states and generations, including Generation X, Millennials, and Generation Z. Data includes names, number of occurences, gender, US States from years 1910 to 2021. Data was filtered by starting letter of name as "C", and gender as male.
![Data Dashboard View on Tableau](/tableau_dashboards/about_data.png)

## Method
- Generational Segmentation: Data was segmented into three generational categories - Generation X, Millennials, and Generation Z. The top male names in each generation were identified based on frequency.
- State-wise Analysis: Additionally, the data was analyzed state by state to observe regional trends. States like CA, IL, NY, PA, and TX were specifically examined.
![Dataset Manipulation Dashboard View on Tableau](/tableau_dashboards/dataset_manipulation.png)

## Analysis of Name Popularity Over Time
Objective: Investigate if time influences name choices, specifically in the context of male names across different generations.
Approach: Analyzed top male names for Generation X, Millennials, and Generation Z, identifying trends in their popularity.
Findings: Noticed that names like Christopher, Charles, and Carl were repeatedly popular, with some variations across generations.
![Generational Analysis View on Tableau](/tableau_dashboards/generational_analysis.png)

## Influence of Location on Name Choices
To examine if and how location affects the popularity of names, with a dual focus on specific states and broader regional trends in the USA.
Approach
- State-Wise Analysis: Investigated the popularity of male names in various states including California (CA), Illinois (IL), New York (NY), Pennsylvania (PA), and Texas (TX). This analysis assessed the influence of factors like population density and regional culture on naming trends.
- Regional Analysis: Extended the study to a regional level, comparing the top three male names across various US regions, with a specific emphasis on the Southern states.
Findings
- State-Wise Trends: Observed that neighboring states often shared common top names, indicating that cultural factors significantly influence name popularity within these areas.
- Regional Trends: In the broader regional analysis, names like Carl, Charles, and Calvin were found to be consistently popular in the South. This consistency suggests a strong regional preference in naming conventions, highlighting the impact of cultural and societal influences on naming trends across different regions of the USA.
![Regional Analysis View on Tableau](/tableau_dashboards/regional_analysis.png)

## Findings and Insights
Certain male names like Christopher and Charles have maintained popularity across multiple generations.
Regional cultural differences significantly influence naming trends, with neighbor states often sharing popular names.

## Privacy and Data Considerations
This project uses publicly available data with no personal or sensitive information.

## Author
- [Muge Kosar](https://github.com/mugekosar)



