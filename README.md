# 🎓 Global Education Cost Analysis – EDA  

_Analyzing tuition, living costs, visa fees, and insurance across top countries and universities using Python and visualization libraries._  

---

## 📌 Table of Contents  
- <a href="#overview">Overview</a>  
- <a href="#business-problem">Business Problem</a>  
- <a href="#dataset">Dataset</a>  
- <a href="#tools--technologies">Tools & Technologies</a>  
- <a href="#project-structure">Project Structure</a>  
- <a href="#data-cleaning--preparation">Data Cleaning & Preparation</a>  
- <a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA)</a>  
- <a href="#research-questions--key-findings">Research Questions & Key Findings</a>  
- <a href="#visualizations">Visualizations</a>  
- <a href="#how-to-run-this-project">How to Run This Project</a>  
- <a href="#final-recommendations">Final Recommendations</a>  
- <a href="#author--contact">Author & Contact</a>  

---

## Overview  

This project explores the **global costs of education abroad** by analyzing tuition fees, rent, living expenses, visa, and insurance costs. The aim is to identify affordability trends, categorize tuition levels, and uncover geographic or academic factors that drive expenses for students planning to study overseas.  

---

## Business Problem  

Studying abroad requires careful financial planning. Students, universities, and policymakers face challenges in:  

- Understanding country-wise and city-wise cost variations  
- Identifying programs with high tuition and living expenses  
- Categorizing affordability into clear tuition bands  
- Highlighting outliers such as zero/invalid tuition values  
- Correlating tuition with living costs, rent, and visa expenses  

---

## Dataset  

- Source: Custom CSV dataset containing global education costs  
- Records: **907**  
- Features include:  
  - **Country, City, University, Program, Level**  
  - **Duration (Years)**  
  - **Tuition (USD), Living Cost Index, Rent (USD)**  
  - **Visa Fee, Insurance, Exchange Rate**  

---

## Tools & Technologies  

- **Python** (Pandas, NumPy)  
- **Visualization** (Matplotlib, Seaborn, Plotly)  
- **Jupyter Notebook / Google Colab**  
- **GitHub** for version control  

---

## Project Structure  

global_education_cost_analysis_eda/
│
├── README.md
├── requirements.txt
│
├── data/                        # Dataset files
│   └── International_Education_Costs.csv
│
├── notebooks/                   # Jupyter notebooks
│   └── Global_Education_Cost_Analysis.ipynb
│
└── images/                      # Visualizations & charts
    ├── tuition_distribution.png
    ├── correlation_heatmap.png
    └── sunburst_chart.png
