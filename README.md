# Global-Air-Quality-Analytics-Case-Study
A data analytics project using Excel and Power BI to explore AQI patterns, compare country averages, examine pollutant measures, and present key findings through an interactive dashboard.

# SWYNEX Final Data Analytics Project: Global Air Quality Analytics Case Study

Task 4 of the SWYNEX Technologies Data Analyst Internship (6 October to 5 November 2026).
Intern: Rahmatu Husein | Intern ID: SWX-APP-2026-6E65A

## Project Overview

This project analyses the Global Air Pollution Dataset to show how air quality is distributed, which pollutant drives the index and where the highest averages appear. Excel was used to clean the data and calculate statistics, and Power BI was used to build an interactive dashboard. The work follows six steps: ask, prepare, process, analyze, share and act.

## Problem Statement

A dataset with more than twenty thousand air quality records cannot be understood one row at a time. Decision makers need it cleaned, summarised and shown in a form they can read in a few minutes. The project answers four questions:

✓ How good or poor is air quality across the records, and how are the readings distributed?
✓ Which pollutant has the greatest influence on the overall AQI?
✓ Which countries show the highest average AQI?
✓ How can the results be presented so that decision makers can explore them easily?

## Dataset

Source: Global Air Pollution Dataset on Kaggle, published by hasibalmuzdadid.
https://www.kaggle.com/datasets/hasibalmuzdadid/global-air-pollution-dataset

The prepared workbook holds 23,463 records, with country, the overall AQI value and category, and the AQI values and categories for PM2.5, ozone, nitrogen dioxide and carbon monoxide.

## Data Cleaning Process

Cleaning was done in Excel and recorded in two worksheets, Cleaned_Data and Data_Audit.

✓ Reviewed the field headings and layout.
✓ Labelled missing country values as Unknown instead of deleting the rows.
✓ Checked for duplicate records; none were reported.
✓ Left Unknown rows out of the country averages only, so overall figures are unaffected.

## Analysis

| Measure | Result |
| --- | --- |
| Prepared records | 23,463 |
| Mean overall AQI | 72.01 |
| Median overall AQI | 55 |
| Mode | 50 |
| Range | 6 to 500 |
| Skewness | about 3.29 |
| Good records | 9,936 (42.3%) |
| Moderate records | 9,231 (39.3%) |
| Unhealthy for Sensitive Groups or worse | 4,296 (18.3%) |
| Hazardous records | 191 (0.8%) |
| Highest pollutant average | PM2.5 (68.52) |

The Republic of Korea recorded the highest country average (421.00), followed by Bahrain (188.00), Mauritania (179.00), Pakistan (178.79) and the United Arab Emirates (163.67). Country averages describe the records supplied and are not a ranking of national air quality.

## Dashboard

The Global Air Quality Dashboard in Power BI shows the average AQI, total records, the category distribution, a pollutant visual, a map of average AQI by country and a slicer that filters every visual by AQI category.



<img width="1080" height="609" alt="WhatsApp Image 2026-11-01 at 14 32 17" src="https://github.com/user-attachments/assets/44edc7ff-23e2-4e65-a7eb-ca5d4cfef322" />


## Key Business Insights

| Insight | Evidence | Decision it supports |
| --- | --- | --- |
| Most records show acceptable air | Good and Moderate make up 81.7% of records | Use as the baseline for spotting unusual locations or periods |
| Attention belongs on the tail | 18.3% of records carry health warnings; 191 are Hazardous | Set alerts on the share of high AQI records |
| One average is not enough | Mean 72.01 against median 55 | Report the median and category shares with the mean |
| Particulate matter drives the index | PM2.5 averages 68.52, close to the overall mean | Prioritise fine particles in monitoring and mitigation |
| Country averages need context | Korea averages 421.00, over twice the next country | Show record counts and period beside country averages |

## Top Three Recommendations

› Monitor the high end of the scale. Base alerts on the share of records at Unhealthy for Sensitive Groups or worse (18.3%), supported by the median and category counts.
› Put fine particles first. Give PM2.5 monitoring and reduction the highest priority when resources are limited.
› Use the dashboard as the standard view. Show record counts and time coverage beside any country comparison so that results are read fairly.

## Scope and Limitations

✓ The analysis covers the records in the selected Kaggle dataset, and country averages are read alongside record counts.
✓ It is descriptive: it shows how AQI is spread and which pollutant leads.
✓ The fields examined carry no dates, so trends over time are a natural next step.

## Repository Contents

| File | Description |
| --- | --- |
| SWYNEX_Final_Data_Analytics_Project_Concise.pdf | The project write-up |
| Global_Air_Quality_Analysis.xlsx | Cleaned data, audit sheet, statistics and charts |
| Global_Air_Quality_Dashboard.pbix | The Power BI dashboard |
| images/dashboard.png | Dashboard screenshot |

## Tools

Microsoft Excel, Microsoft Power BI

## References

✓ Google. Google Data Analytics Capstone: Complete a case study. Coursera.
✓ U.S. Environmental Protection Agency. Air Quality Index (AQI) basics. AirNow.
