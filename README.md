# Telco Churn Analysis

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

A churn-focused analytics workflow that ingests raw customer profiles, telecom plan information, and churn status, leveraging python statistical modeling to uncover churn trends and constructs customer segments to inform an actionable retention strategy for the organization.

---

## Business Case & Objectives
The organization in question aims to reduce customer churn and maintain a healthy portfolio, but lacks visibility into what variables affect customer churn.

This project aims to uncover which variables have the highest correlation with customer churn and define customer segments in order to construct a high-value customer retention strategy.

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
git clone [https://github.com/rykerboeh/telco-churn-python.git](https://github.com/rykerboeh/telco-churn-python.git)
cd telco-churn-python
```

### 2. Set Up the Python Environment
Install dependencies using the provided environment specifications:

```bash
pip install -r requirements.txt
```

### 3. Execute the Analytical Notebook

* Run notebooks/carbon_footprint_net_zero.ipynb 

Developed by Ryker Boeh — Connect with me on https://www.linkedin.com/in/rboeh
