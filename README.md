# Telco Churn Analysis

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Microsoft Office](https://img.shields.io/badge/Microsoft_Office-D83B01?style=for-the-badge&logo=microsoft-office&logoColor=white)
![Microsoft Word](https://img.shields.io/badge/Microsoft_Word-2B579A?style=for-the-badge&logo=microsoft-word&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)


## Overview
This project aims to clean and explore crime incident data from a user-input simulated dataset sourced from Kaggle. The dataset required extensive cleaning and standardization to handle typos, inconsistent inputs, and missing data. The messy data was processed in SQL and explored to uncover big picture crime metrics and potential trends.

## Project Structure

    ├── README.md          <- README .
    ├── query              <- Code of the DB cleaning and exploratory queries.
    │   │
    │   └── crime_incident_cleaning_queries.sql    <- Cleaning queries for raw dataset.
    │   └── crime_analysis_queries.sql             <- Exploratory analysis queries.
    │
    ├── src            <- Source for this project.
        │
        ├── crime_incidents_messy.csv     <- Dataset used for this project.
        
--------

## Dataset
The dataset used in this project contains mock crime reports ranging from 2018-2024. It is meant to simulate a database of user-input instances containing data such as suspect information, victim information, officer information, crime type, weapon used, case status, resolution, etc. 

<img width="1067" height="493" alt="crime_incident_dirty" src="https://github.com/user-attachments/assets/89629d38-f617-47c4-ae2c-4f191fa8b7ea" />


## Database
To facilitate data management and analysis, a SQL database has been created to store the dataset. SQL provides a robust and efficient way to query and manipulate the data. The database schema has been designed to ensure proper organization and ease of use. The structure of the database enables seamless integration with various data visualization tools.

## Data Processing
The data contained in this Kaggle dataset requires some preprocessing to clean and transform it into a suitable format for analysis. The raw data has inconsistent formatting, typos, and missing data. SQL queries were utilized to clean, filter, and transform the data as necessary. This ensures that the data used for analysis is accurate and reliable.

<img width="1088" height="492" alt="crime_incident_clean" src="https://github.com/user-attachments/assets/f40d9350-570b-4298-95b8-2650d6765a95" />


## Analysis includes:

**Most Common Crime Type:** Totals of the most frequently reported crime types.

**Crime Trends Over Time:** Representation of how crime volume has fluctuated over the years, by crime type.

**Arrest Rate By Crime Type:** Likelihood of an arrest by crime type.

**District and City Hotspot Ranking:** Representations of crime volume by city and district.

**Time of Day Incident Analysis:** Exploration of when incidents may be most likely to occur.

**Rolling Crime Trends:** Visualization of 7-day and 30-day rolling crime totals and averages.

## Technologies Used
**SQL:** For data extraction, transformation, and loading into the database.

**Database Management System:** PostgreSQL to host and manage the dataset.


**Programming Languages:**  SQL for data processing and scripting.



**Conclusion**
The crime incidents project aims to leverage SQL to clean and standardize a messy user-input dataset and provide general insights on crime volume and reveal potential crime trends. This project is valuable for policymakers, residents, and law enforcement interested in crime data of the relevant cities/disticts.

## Author
- <ins><b>©2023 Ryker Boeh. All rights reserved</b></ins>
- <b>[LinkedIn](https://www.linkedin.com/in/rboeh/)</b>

## Contact me

If you have any questions, suggestions, or just want to say hello, you can reach out to me at [Ryker Boeh](mailto:rykerbboeh@gmail.com). I would love to hear from you.
