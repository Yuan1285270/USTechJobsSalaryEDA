# Tech Jobs US – Salary Analysis & Job Market Insights

This project analyzes the **US tech job market** by integrating job listing data from both a **Kaggle dataset** and the **Adzuna Job Search API**.

The goal is to explore salary trends and identify factors that influence compensation, including **remote work**, **geographic location**, **company revenue**, and **programming languages**.

---

## Features

- **Data Collection**
  - Imported large-scale job dataset from Kaggle
  - Retrieved additional job postings via **Adzuna API** (REST API)

- **Data Cleaning & Standardization**
  - Unified salary formats into **annual full-time USD**
  - Standardized inconsistent fields across multiple data sources
  - Removed invalid or incomplete job entries

- **Exploratory Data Analysis (EDA)**
  - Salary comparison: **Remote vs On-site**
  - Salary distribution across **states/cities**
  - Salary trends by **company revenue**
  - Salary differences across **programming language requirements**

- **Visualization**
  - Salary distribution plots
  - Location-based salary comparison charts
  - Feature-based salary trend insights

---

## Tech Stack

- Python
- Pandas / NumPy
- Matplotlib / Seaborn
- Jupyter Notebook
- REST API Integration (Adzuna API)
- Excel (data preprocessing / export)

---

## Dataset Sources

- Kaggle Dataset (US tech job listings)
- Adzuna API (job postings retrieved programmatically)

> Note: Due to GitHub file size limitations, large `.xlsx` datasets are not uploaded to this repository.

---

## How to Run

### 1. Clone Repository

git clone https://github.com/Yuan1285270/TechJobsUS.git  
cd TechJobsUS  

### 2. Install Dependencies

pip install pandas numpy matplotlib seaborn requests openpyxl openpyxl  

### 3. Run Notebook

jupyter notebook  

Open `FinalProject.ipynb`.

---

## Key Insights (Summary)

This project provides insights into:

- The salary impact of **remote work**
- Which **locations** offer higher compensation
- How **company revenue** correlates with salary
- Which **programming skills** are associated with higher-paying jobs

---

## Future Improvements

- Apply robust outlier handling (IQR / percentile clipping / log-scale visualization)
- Automate ETL pipeline (API → cleaning → database storage)
- Build an interactive dashboard (Streamlit / Tableau)
- Train a salary prediction model using job description features

---

## Author

**Tsung-Yuan Lin**  
GitHub: [Yuan1285270](https://github.com/Yuan1285270)  
LinkedIn: [tsungyuan0218](https://www.linkedin.com/in/tsungyuan0218/)  
Email: t3good1@gmail.com
