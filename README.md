# EPA Grant Distribution Analysis

## Overview
Cleaned, organized, and performed data analysis on 18,000+ Environmental Protection Agency (EPA) grant records from 1974 - 1980. With the cleaned data created an interactive dashboard with a map of our data on arcGIS 

## Objective
The goal of this project is to create a structured, accessible dataset that allows researchers to examine historical EPA grant distribution patterns and evaluate regional differences in federal environmental funding backup our own claims that certain regions get more financial support from the government than others

## Data
Before our project, there was not publicly available data of EPA grants from 1974 - 1980. We were able to contact the government to acquire the data, but it was in thousands of pdf scans. Thus, the original spreadsheets were made from using text recognition software (transkribus) to map certain areas of the pdf to a column in a spreadsheet. The data represents lots of different information about each grant, such as award amount, location(city, state, zipcode, etc.), population, and more.

##arcGIS Dashboard
link: https://www.arcgis.com/apps/dashboards/7ccd90d6266140d388b2f592396767ab

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
- Locations with a lower population got more grants on average
- Geographic mapping revealed regional differences in EPA grant distribution patterns

## Folders
- code: R code that I utilized in the cleaning and analysis process. README.docx describes specifics of every file
- data: there are 3 subfolders
  - original: The versions of the data I was given from the results from the text recognition software (transkribus) 
  - cleaned: Cleaned versions of the spreadsheets in the original folder. also includes combined master spreadsheet. More details on specifics of each file in README.pdf
  - extra: additional spreadsheets I used to add information to my master file for mapping / statistics purposes. More details on specifics of each file in README.pdf
- documents: files listing my documentation process for each step of the project and slideshows I have used in presenting my project. As this project is ongoing, the documentation files will be further updated in the future. For more in depth commentary on my steps in this project, read the documentation
- visualizations: Cleaned up versions of graphs I have created as part of my R code. Graphs showcase general findings from when I conducted analysis

## How to Run
1. Download or clone this repository.
2. Open the R Markdown files in the code folder.
3. To reproduce year-specific cleaning scripts, place the corresponding raw spreadsheet from the original folder in the working directory.
4. To run the main analysis file, use the cleaned master spreadsheet located in the cleaned folder.
5. Some final GIS-ready transformations were completed through a combination of R, Excel, and ArcGIS and may not be fully reproducible from code alone.

## Notes
- This project is still ongoing. This repository will be updated throughout the process.

