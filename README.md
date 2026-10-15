# EPA Grant Distribution Analysis

## Overview
Cleaned, organized, and performed data analysis on 18,000+ Environmental Protection Agency (EPA) grant records from 1974 - 1980. With the cleaned data created an interactive dashboard with a map of our data on arcGIS (link: https://www.arcgis.com/apps/dashboards/7ccd90d6266140d388b2f592396767ab)

## Objective
The goal of this project is to create a structured, accessible dataset that allows researchers to examine historical EPA grant distribution patterns and evaluate regional differences in federal environmental funding backup our own claims that certain regions get more financial support from the government than others

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
- Geographic mapping revealed regional differences in EPA grant distribution patterns

## Folders
- code: R code that I utilized in the cleaning and analysis process. README.docx describes specifics of every file
- data: there are 3 subfolders
  - original: The versions of the data I was given from the results from the text recognition software (transkribus) 
  - cleaned: Cleaned versions of the spreadsheets in the original folder. also includes combined master spreadsheet. More details on specifics of each file in README.docx
  - extra: additional spreadsheets I used to add information to my master file for mapping / statistics purposes. More details on specifics of each file in README.docx
- documents: files listing my documentation process for each step of the project and slideshows I have used in presenting my project. As this project is ongoing, the documentation files will be further updated in the future. For more in depth commentary on my steps in this project, read the documentation
- visualizations: Cleaned up versions of graphs I have created as part of my R code. Graphs showcase general findings from when I conducted analysis

## How to Run
The grant1974.Rmd - grant1980.Rmd files can be ran with the original spreadsheet files in the same folder. As I acquired the final cleaned versions of each year's grant spreadsheet through Excel itself, they cannot exactly be recreated by hand (without a lot of time put into it). Thus for my grantsdataanalysis.Rmd file use the cleaned versions of the grant files in the same folder. Extra additions to the master file that got it to the GIS master file was done through a variety of methods in and out of R, and mostly all other files should work as intended with the master file and if not the file will say so. More specifics are detailed in the respective README.docx files.

## Notes
- This project is still ongoing. This repository will be updated throughout the process.
- ArcGIS dashboard link: https://www.arcgis.com/apps/dashboards/7ccd90d6266140d388b2f592396767ab

