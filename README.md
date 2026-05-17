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
This project aims to explore and analyze a telcom customer churn dataset to identify major drivers of customer churn and recommend a retention strategy.

## Project Structure

    ├── README.md          <- README .
    ├── code              <- Code of the DB preprocessing and analysis
    │   │
    │   └── telco_churn_analysis.ipynb    <- Preprocessing and analysis for telco dataset
    │
    ├── src            <- Source for this project.
        │
        ├── telco_churn_data.csv     <- Dataset used for this project.
        
--------

## Dataset
The dataset used in this project contains sample churn data from a telecommunication company. Values include contract type, contract add-ons, monthly charge, total charges, contract status, churn rating, tenure in months, and churn reason.

## Database
To facilitate data management and analysis, the dataset was read into a python jupyter notebook. Python provides access to dynamic analytic libraries such as numpy, pandas, matplotlib, and seaborn enabling churn analysis, correlation analysis, and customer segmentation. 

## Data Processing
The data contained in this Kaggle dataset was relatively clean for this application. Python was used to explore the dataset's shape, schema, and datatypes. It was then used to rule out duplicate rows and missing data and ensure consistent formatting.

## Analysis includes:

**Customer Churn Count and Rate:** How many customers churned, joined, and stayed during the reporting period. Represented as raw customer count, gross customer churn rate, and net customer churn rate.

**Revenue Churn Rate:** What percent of revenue churned, stayed, and joined?

**Churn by Contract Type:** What contract types churned the most?

**Contract Type by Offer:** Does the signing offer affect contract type?

**Churn Rate by Contract Add-On:** Which contracts have higher/lower correlation to customer churn?

**Correlation with Churn:** Which numerical variables have most significant correlation to customer churn?

**Customer Segmentation:** Analyze churn by customer segments. Segments include tenure group, spending tier, and value segments.

## Technologies Used
**Python:** For data extraction, transformation, and loading into the database.

**Database Management System:** Jupyter Notebook to host and manage the dataset.


**Programming Languages:**  Python for data processing and analysis.

**Conclusion**
The telco churn project aims to leverage python to clean and analyze sample customer churn data to provide valuable churn insights and an actionable retention strategy for company stakeholders.

## Author
- <ins><b>©2023 Ryker Boeh. All rights reserved</b></ins>
- <b>[LinkedIn](https://www.linkedin.com/in/rboeh/)</b>

## Contact me

If you have any questions, suggestions, or just want to say hello, you can reach out to me at [Ryker Boeh](mailto:rykerbboeh@gmail.com). I would love to hear from you.
