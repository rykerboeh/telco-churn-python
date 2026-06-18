# Telco Churn Analysis

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

An end-to-end data engineering and analytics pipeline that ingests raw, multi-source building utility consumption data, implements a tiered SQL cleaning and aggregation workflow, constructs a 2030 net-zero forcast model in Python, and produces an executive-ready emissions dashboard in Tableau.

This project aims to explore and analyze a telcom customer churn dataset to identify major drivers of customer churn and recommend a retention strategy. 

---

## Business Case & Objectives
The organization in question aims to acheive a net-zero carbon footprint, but lacks visibility into what business activities and real estate assets are driving environmental liabilities. The raw data is fragmented across multiple databases.

This project aims to centralize the fragmented data into a unified consumption database, calculate a functional weighted carbon intensity metric, and craft a "business-as-usual" projection to track consumption against 2030 net-zero milestones.

The telco churn project aims to leverage python to clean and analyze sample customer churn data to provide valuable churn insights and an actionable retention strategy for company stakeholders.

---

## Tech Stack & Tools
* **Data Pipeline & Analytics:** Python (Pandas, NumPy, Jupyter Notebooks)
* **Database Management** Jupyter Notebook (Host and manage dataset)

---

## Repository Structure
```text
├── data/
│   ├── raw/                        # Source Kaggle data
│       └── telco_churn_data.csv
├── notebooks/                      # Data modeling & analytics
│   └── telco_churn_analysis.ipynb
├── requirements.txt                # Enforces reproducible Python execution environment
└── README.md                       # Master project documentation
```
---

## Data Analysis Architechure and Key Fields

* **Customer Churn Count and Rate:** How many customers churned, joined, and stayed during the reporting period. Represented as raw customer count, gross customer churn rate, and net customer churn rate.
* **Revenue Churn Rate:** What percent of revenue churned, stayed, and joined?
* **Churn by Contract Type:** What contract types churned the most?
* **Contract Type by Offer:** Does the signing offer affect contract type?
* **Churn Rate by Contract Add-On:** Which contracts have higher/lower correlation to customer churn?
* **Correlation with Churn:** Which numerical variables have most significant correlation to customer churn?
* **Customer Segmentation:** Analyze churn by customer segments. Segments include tenure group, spending tier, and value segments.
  
---

## How to Reproduce & Run Locally

### 1. Clone the Repository
```bash
git clone [https://github.com/rykerboeh/net-zero-analytics-pipeline.git](https://github.com/rykerboeh/net-zero-analytics-pipeline.git)
cd net-zero-analytics-pipeline
cd net-zero-analytics-pipeline
```

### 2. Set Up the Python Environment
Install dependencies using the provided environment specifications:

```bash
pip install -r requirements.txt
```

### 3. Source the Raw Data
* Download the raw building and telemetry datasets directly from https://www.kaggle.com/datasets/cdaclab/unicon/data.

* Place the raw files into your local data/raw/ directory (Note: This directory is blocked by .gitignore to protect storage boundaries).

### 4. Execute the SQL Pipeline & Analytical Notebook
* Run files 01_ through 03_ in your preferred SQL relational database management engine to build the underlying target structures.

* Run notebooks/carbon_footprint_net_zero.ipynb to generate the processed CSV data output files.

* Open dashboard/executive_emissions_overview.twbx using Tableau Desktop or Tableau Public to explore the user interface.


Developed by Ryker Boeh — Connect with me on https://www.linkedin.com/in/rboeh


## Dataset
The dataset used in this project contains sample churn data from a telecommunication company. Values include contract type, contract add-ons, monthly charge, total charges, contract status, churn rating, tenure in months, and churn reason.

## Database
To facilitate data management and analysis, the dataset was read into a python jupyter notebook. Python provides access to dynamic analytic libraries such as numpy, pandas, matplotlib, and seaborn enabling churn analysis, correlation analysis, and customer segmentation. 

## Data Processing
The data contained in this Kaggle dataset was relatively clean for this application. Python was used to explore the dataset's shape, schema, and datatypes. It was then used to rule out duplicate rows and missing data and ensure consistent formatting.
