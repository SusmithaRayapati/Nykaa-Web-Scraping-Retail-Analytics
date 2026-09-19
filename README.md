# 🛍️ Nykaa Retail Analytics: Web Scraping, Data Cleaning & Power BI Dashboard

## 📌 Project Overview

This project focuses on collecting retail product data from the **Nykaa website** through web scraping and transforming it into a structured dataset for analysis and visualization.

Data was collected from three major categories:

* 💄 Beauty
* 🏥 Healthcare
* 👶 Baby

The three scraped datasets were combined into a single dataset, cleaned and prepared for analysis. The final dataset was then used to build an interactive **Power BI dashboard** to explore product, pricing, discount, rating, brand, and category-level insights.

---

## 🎯 Objectives

* Collect product data from the Nykaa website using web scraping.
* Create separate datasets for Beauty, Healthcare, and Baby categories.
* Combine the scraped datasets into a single dataset.
* Clean and standardize the collected data.
* Perform exploratory data analysis.
* Identify useful retail and product-level insights.
* Build an interactive Power BI dashboard for visualization.

---

## 🔄 Project Workflow

```text
Nykaa Website
      ↓
Web Scraping
      ↓
Beauty | Healthcare | Baby
      ↓
Three Raw CSV Files
      ↓
Data Combination
      ↓
Data Cleaning & Transformation
      ↓
Final Cleaned Dataset
      ↓
Data Analysis
      ↓
Power BI Dashboard
```

---

## 🗂️ Dataset Structure

### Raw Datasets

The raw scraped datasets are maintained separately:

```text
data/
└── raw/
    ├── beauty_raw.csv
    ├── healthcare_raw.csv
    └── baby_raw.csv
```

### Final Dataset

After combining and cleaning the three datasets:

```text
data/
└── processed/
    └── nykaa_cleaned_combined.csv
```

Keeping the raw and processed datasets separately helps maintain a clear data pipeline and makes the transformation process easier to understand.

---

## 🧹 Data Cleaning & Preparation

The combined dataset was prepared for analysis through steps such as:

* Handling missing values
* Removing duplicate records
* Standardizing product/category information
* Cleaning price and discount-related fields
* Formatting numerical columns
* Preparing categorical fields for analysis
* Validating the final dataset

---

## 📊 Analysis

The cleaned dataset was analyzed to understand:

* Product distribution across categories
* Brand-level performance
* Product pricing
* Discount patterns
* Customer ratings
* Category-level trends
* Product availability and other relevant attributes

---

## 📈 Power BI Dashboard

An interactive Power BI dashboard was created using the final cleaned dataset.

### Dashboard Highlights

* Total Products
* Total/average pricing metrics
* Discount analysis
* Product category analysis
* Brand analysis
* Rating-based analysis
* Interactive filters and slicers
* Category-level comparisons

The dashboard provides a visual overview of the Beauty, Healthcare, and Baby retail categories.

---

## 🛠️ Tools & Technologies

* **Python**
* **Web Scraping**
* **Pandas**
* **NumPy**
* **Jupyter Notebook**
* **CSV**
* **Power BI**
* **Power Query**
* **DAX**

---

## 📁 Project Structure

```text
Nykaa-Retail-Analytics/
│
├── data/
│   ├── raw/
│   │   ├── beauty_raw.csv
│   │   ├── healthcare_raw.csv
│   │   └── baby_raw.csv
│   │
│   └── processed/
│       └── nykaa_cleaned_combined.csv
│
├── scraping/
│   └── nykaa_web_scraping.ipynb
│
├── analysis/
│   └── nykaa_analysis.ipynb
│
├── dashboard/
│   └── Nykaa_Retail_Analytics.pbix
│
├── README.md
└── requirements.txt
```

---

## 💡 Key Learning

This project provided practical experience in building an end-to-end data workflow, from **web data collection and dataset preparation to analysis and Power BI visualization**.

