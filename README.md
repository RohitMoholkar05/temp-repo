## DATA ANALYTICS PORTFOLIO

This repository contains data analytics projects focused on data collection, data cleaning, exploratory analysis, visualization, SQL reporting, dashboard development, and insight generation. The projects demonstrate end-to-end analytics workflows using Python, SQL, Tableau, and reporting tools across real-world datasets.

## 📌 Project Highlights

| Project | Domain | Tools | Dataset Size | Key Output |
|---|---|---|---:|---|
| [Rental Property Market Analysis](rental-property-market-analysis) | Real Estate Analytics | Python, Selenium, BeautifulSoup, Pandas, Matplotlib, Seaborn | 2,478 rows x 10 columns | Rental market analysis with scraped property listings, EDA, and housing trend insights |
| [Job Market Analysis](job-market-analysis) | Workforce Analytics | Python, Pandas, NumPy, Matplotlib, Seaborn, JSON | 1,615,940 rows x 23 columns | Large-scale job posting analysis covering sectors, roles, hiring trends, and skill patterns |
| [Restaurant Market Health Violations](restaurant-market-health-violations) | Public Health Analytics | SQL Server, Star Schema, Tableau, Reporting Services | 313,676 rows x 17 columns | Data warehouse schema, SQL reporting, Tableau dashboard, and violation trend analysis |

## 📊 Dataset Sources

| Project | Dataset | Source | Key Features |
|---|---|---|---|
| Rental Property Market Analysis | NoBroker Rental Listings | Web Scraped Dataset | Rent, deposit, area, maintenance, furnishing, property type, preferred tenants, availability, location |
| Job Market Analysis | Job Description Dataset | [Kaggle](https://www.kaggle.com/datasets/ravindrasinghrana/job-description-dataset) | Job titles, roles, company details, sectors, skills, responsibilities, experience, qualifications, work type |
| Restaurant Market Health Violations | LA Restaurant & Market Health Data | [Kaggle](https://www.kaggle.com/datasets/cityofLA/la-restaurant-market-health-data?select=restaurant-and-market-health-violations.csv) | Violation codes, facility details, inspection dates, violation status, program elements, scores, service types |

Large external datasets are not included in this repository due to file size and source management considerations. Dataset download instructions are provided inside the respective project `data` folders.

## 📂 Repository Structure

```text
data-analytics/
├── README.md
├── requirements.txt
├── .gitignore
├── rental-property-market-analysis/
│   ├── rental_property_market_analysis.ipynb
│   ├── data/
│   │   └── rental_property_listings.csv
│   └── documents/
│       └── rental_property_market_analysis_report.pdf
├── job-market-analysis/
│   ├── job_market_analysis.ipynb
│   └── data/
│       └── README.md
└── restaurant-market-health-violations/
    ├── assets/
    │   ├── restaurant_market_health_violations_dashboard.png
    │   └── star_schema.png
    ├── data/
    │   └── README.md
    ├── diagrams/
    │   └── star_schema.drawio
    ├── documents/
    │   ├── restaurant_market_health_violations_report.pdf
    │   └── restaurant_market_health_violations_presentation.pdf
    ├── reports/
    │   ├── cases_by_program_element.pdf
    │   ├── ratio_by_services.pdf
    │   ├── tabular_report.pdf
    │   └── trend_of_health_violation.pdf
    └── sql/
        └── restaurant_market_health_violations_schema.sql
```

## 🧩 Skills Demonstrated

- Data collection and data preparation
- Web scraping with Selenium and BeautifulSoup
- Data cleaning and transformation
- Exploratory data analysis
- Data visualization and reporting
- Large-scale dataset analysis
- JSON parsing and feature extraction
- SQL database design
- Star schema modeling
- Dimensional data warehousing
- Tableau dashboard development
- SQL reporting and PDF report generation
- Analytical interpretation and insight generation

## 💻 Technology Stack

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- BeautifulSoup
- Selenium
- lxml
- JSON
- SQL Server
- Tableau
- Reporting Services

## 📚 Project Summaries

### Rental Property Market Analysis

This project analyzes rental property listings collected from NoBroker.com. The workflow includes web scraping, data cleaning, preprocessing, exploratory data analysis, and visualization.

The analysis focuses on rent, deposit, area, maintenance, furnishing type, property type, preferred tenants, availability, and location. Key findings highlight differences between furnished and unfurnished properties, variation across prime localities, and the relationship between rent and deposit.

### Job Market Analysis

This project analyzes a large-scale job posting dataset from Kaggle covering job descriptions across multiple sectors and roles. The workflow includes data cleaning, column reduction, datatype correction, missing-value handling, JSON parsing, exploratory analysis, and visualization.

The analysis explores hiring trends, sector-level demand, role distribution, and job requirement patterns. The cleaned dataset structure supports deeper analysis of job market behavior and employment trends over time.

### Restaurant Market Health Violations

This project analyzes LA restaurant and market health violation data using SQL, dimensional modeling, reporting, and dashboard visualization. The workflow includes SQL Server database design, landing table creation, star schema modeling, fact and dimension table design, SQL reporting, and Tableau dashboard development.

The project includes a star schema model, SQL schema script, Tableau dashboard screenshot, reporting outputs, and presentation/report documents. The analysis focuses on violation cases by city, service type, year, and program element category.

## ▶️ Running the Notebooks

Install the required Python dependencies:

```bash
pip install -r requirements.txt
```

Open Python-based project notebooks using Jupyter Notebook or VS Code:

```bash
jupyter notebook
```

For projects using external datasets, download the datasets from the linked sources and place them in the respective project `data` folders using the filenames described in each `data/README.md`.

## 🚀 Purpose

The purpose of this repository is to present practical data analytics projects in a clean, structured, and well-documented format. These projects demonstrate how real-world data can be collected, cleaned, modeled, analyzed, visualized, and reported to support interpretation, reporting, and decision-making.
