# EPA Grant Distribution Analysis

## Overview
Cleaned, organized, and performed data analysis on 18,000+ Environmental Protection Agency (EPA) grant records from 1974 - 1980. With the cleaned data created an interactive dashboard with a map of our data on arcGIS (link: https://www.arcgis.com/apps/dashboards/7ccd90d6266140d388b2f592396767ab)

## Objective
Create a resource for not only us, but other researchers to analyze and ask questions about the distribution of EPA grants and backup claims that certain regions get more support than others

## Data
Before our project, there was not publicly available data of EPA grants from 1974 - 1980. We were able to contact the government to acquire the data, but it was in thousands of pdf scans. Thus, the original spreadsheets were made from using text recognition software (transkribus) to map certain areas of the pdf to a column in a spreadsheet. The data represents lots of different information about each grant, such as award amount, location(city, state, zipcode, etc.), population, and more.

## Tools Used
Excel, arcGIS, R. Utilized ggplot and tidyverse packages

## Methods
- Data cleaning
- Data wrangling
- Data visualization
- Data mapping
- Presentation and communication

## Key Findings (in analysis)
- Grants in highly populated locations obtained higher award amounts per on average
- locations with a lower population got more grants on average

## Folders
- code: R code that I utilized in the cleaning and analysis process. README.docx describes specifics of every file
- data: there are 3 subfolders
  - original: The versions of the data I was given from the results from the text recognition software (transkribus) 
  - cleaned: Cleaned versions of the spreadsheets in the original folder. also includes combined master spreadsheet. More details on specifics of each file in README.docx
  - extra: additional spreadsheets I used to add information to my master file for mapping / statistics purposes. More details on specifics of each file in README.docx
- documents:
- visualizations:

## How to Run
Explain how someone can open or run the project.

## Notes
- This project is still ongoing. This repository will be updated throughout the process.
- ArcGIS dashboard link: https://www.arcgis.com/apps/dashboards/7ccd90d6266140d388b2f592396767ab

