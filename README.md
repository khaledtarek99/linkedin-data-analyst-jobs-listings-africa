# LinkedIn Data Analyst Jobs Listings in Africa
![LinkedIn Data Analyst job listings Dashboard](https://user-images.githubusercontent.com/53887110/231547437-ec33775b-c83a-480c-91b7-639ae1896f42.png)

This repository contains Excel workbook that cleans and analyzes and visualizes Data Analyst job listings from LinkedIn in different African countries.
The data was collected from Kaggle and consists of a CSV file with over 2500 job listings. The focus of this analysis was on identifying the most required seniority level, Recruiment Type, and the location of the positions in Africa.

## Table of Contents
* Getting Started
* Prerequisites
* Problem Statement
* Data Cleaning Process
* Analysis Conducted
* Insights Gained
* License

### Getting Started
To get started with this project, simply download the Excel workbook file and open it in Microsoft Excel. The file contains multiple worksheets, each containing analysis and insights on the linkedin_data_analyst_jobs_listings_africa data.
### Prerequisites
Before you begin, make sure you have the following software installed on your machine:
   * Microsoft Excel
## Problem Statement
The main goal of this project is to provide insights and trends in the Data Analyst job market across Africa, assisting myself in making informed decisions.
Now,The first problem i had when seeking for my first job is solved.
## Data Cleaning Process  
* Arabic characters in excel CSV file not displayed correctly, So i used Unicode (UTF-8) in file origin when importing
* Widened the columns
* Translated 360 arabic values in criteria column using Google Sheets GOOGLETRANSLATE() function
* Modified links by removing 'refid' , so that i could identify dublicates
* Checked for misspellings and corrected them
* Checked for duplicates and removed them
* Checked for empty rows and removed them
* Checked for missing values and replaced them with appropriate values (such as mean)
* Renamed columns to have clear and consistent names
* Ensure consistency in data by standardizing formats, units, and values.
## Analysis Conducted
* augmented data by crating new features such as Country, Recruitment type, Seniority level, and Industries
* Grouped the data by onsite_remote and calculated the count of jobs for each workPlace
* Grouped the data by Recruitment type and calculated the count of jobs for each Recruitment type
* Grouped the data by Seniority level and calculated the count of jobs for each Seniority level
* Grouped the data by Seniority level and onsite_remote and calculated the count of jobs for each Seniority level
* Grouped the data by country and calculated the count of jobs for each country
## Insights Gained
The linkedin_data_analyst_jobs_listings_africa dataset was visualized to provide a clear representation of the insights gained from the analysis. The visualizations include Column charts, Bar charts, pie charts, and Map chart in a Dashboard.
* The most required workPlace was onsite, followed by hybrid and remote
* The most required Recruitment type was Full-time
* The most required Seniority level was Entry Level
* The most required workPlace for Entry Level was onsite, followed by remote
* The majority of job listings were in South Africa 

## License

This project is licensed under the MIT License.
