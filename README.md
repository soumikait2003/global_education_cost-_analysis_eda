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

---

## Data Cleaning & Preparation  

- Identified **103 rows with Tuition = 0** → replaced with **country average tuition** (or global average if missing).  
- Created **Tuition Category** feature:  
  - Low, Medium, High, Very High, Extremely High  
- Handled outliers in living cost, visa fee, and rent.  
- Checked for duplicates and missing values.  

---

## Exploratory Data Analysis (EDA)  

**Key Observations:**  
- Tuition distribution is **right-skewed** with many mid-range programs and a few very expensive ones.  
- Rent strongly correlates with both tuition and living cost index.  
- Exchange rate variation shows weak correlation with education costs.  
- USA, UK, and Canada appear frequently as high-cost countries.  
- Specialized programs (Data Science, AI, MBA) tend to be costlier than general programs.  

---

## Research Questions & Key Findings  

1. Which countries and cities have the **highest tuition and living costs**?  
2. Are **PhD and Master’s programs** more expensive than Bachelor’s?  
3. Which programs (e.g. STEM vs non-STEM) show higher cost categories?  
4. What is the correlation between **living cost index, rent, and tuition**?  
5. How do **outliers** (very high/low tuition or rent) impact overall averages?  

---


---

## How to Run This Project  

1. Clone the repository:  
```bash
git clone https://github.com/soumikait2003/global_education_cost-_analysis_eda.git

