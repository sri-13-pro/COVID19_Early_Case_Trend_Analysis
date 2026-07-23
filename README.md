# 🦠 COVID-19 Early Case Trend Analysis & Recovery Insights

## 📌 Project Overview

This project presents an end-to-end healthcare data analytics solution developed to analyze early-stage COVID-19 patient data. The analysis focuses on identifying infection trends, understanding patient demographics, evaluating recovery patterns, and building predictive models to estimate recovery duration.

The project follows a complete data analytics workflow, including data preprocessing, exploratory data analysis (EDA), statistical analysis, hypothesis testing, and machine learning. The insights generated from this study can support evidence-based public health decision-making and healthcare resource planning.

---

# 🏢 Business Context

**HealthGuard Analytics Pvt. Ltd.** is a healthcare data analytics company collaborating with public health authorities to analyze infectious disease data. The organization aims to understand disease spread, recovery behavior, and regional trends during the early stages of an outbreak.

Using patient-level COVID-19 data, this project provides actionable insights that can assist government agencies and healthcare organizations in improving disease surveillance, isolation planning, and resource allocation.

---

# ❓ Problem Statement

Public health authorities require data-driven insights to answer the following questions:

* Who is getting infected?
* How are infections spreading?
* What are the recovery trends?
* Which regions are most impacted?
* Which factors influence patient recovery duration?

The objective is to transform raw healthcare data into meaningful insights that support better public health decisions.

---

# 🎯 Project Objectives

* Perform comprehensive data cleaning and preprocessing.
* Conduct Exploratory Data Analysis (EDA).
* Analyze demographic and regional infection patterns.
* Evaluate recovery timelines and patient outcomes.
* Perform statistical analysis and hypothesis testing.
* Build predictive models to estimate recovery duration.
* Compare multiple regression models.
* Generate actionable business insights and recommendations.

---

# 📂 Dataset Information

The dataset contains patient-level COVID-19 records collected during the early phase of the outbreak.

### Features Included

### Demographics

* Sex
* Birth Year
* Country
* Region

### Infection Details

* Infection Reason
* Infection Order
* Infected By

### Exposure Metrics

* Contact Number

### Timeline Data

* Confirmed Date
* Released Date
* Deceased Date

### Patient Outcome

* Released
* Isolated
* Deceased

---

# 🛠️ Tech Stack

### Programming Language

* Python

### Libraries

* NumPy
* Pandas
* Matplotlib
* Seaborn
* SciPy
* Scikit-learn

### Statistical Techniques

* Descriptive Statistics
* Correlation Analysis
* Independent Samples t-Test
* One-Way ANOVA
* Chi-Square Test

### Machine Learning

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

---

# 📁 Project Structure

```text
COVID19_Early_Case_Trend_Analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── images/
│   ├── demographics/
│   ├── infection_analysis/
│   ├── recovery_analysis/
│   ├── regional_analysis/
│   ├── statistical_analysis/
│   ├── hypothesis_testing/
│   └── predictive_analysis/
│
├── notebooks/
│   └── covid_case_analysis.ipynb
│
├── reports/
│   └── Final_Report.pdf
│
├── src/
│   ├── data_loader.py
│   ├── data_cleaning.py
│   ├── eda.py
│   ├── statistics.py
│   ├── hypothesis_testing.py
│   ├── regression.py
│   ├── visualization.py
│   └── utils.py
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

# 🔄 Project Workflow

```text
Business Understanding
        ↓
Data Collection
        ↓
Data Cleaning
        ↓
Feature Engineering
        ↓
Exploratory Data Analysis
        ↓
Statistical Analysis
        ↓
Hypothesis Testing
        ↓
Predictive Modeling
        ↓
Business Insights
        ↓
Recommendations
```

---

# 📊 Exploratory Data Analysis

The EDA focused on understanding patient demographics, infection characteristics, recovery behavior, and geographical trends.

Key analyses include:

* Gender Distribution
* Age Distribution
* Country Distribution
* Infection Reason Analysis
* Infection Order Analysis
* Contact Exposure Analysis
* Patient Outcome Analysis
* Recovery Duration Analysis
* Regional Analysis

---

# 📈 Statistical Analysis

The project includes quantitative analysis using:

* Descriptive Statistics
* Correlation Matrix
* Correlation Heatmap
* Feature Relationship Analysis

These analyses provide statistical evidence supporting the observed data patterns.

---

# 🧪 Hypothesis Testing

The following statistical tests were performed:

* Independent Samples t-Test
* One-Way ANOVA
* Chi-Square Test

These tests validate whether observed differences in recovery duration and patient outcomes are statistically significant.

---

# 🤖 Machine Learning Models

Three regression models were developed and evaluated:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

Models were evaluated using:

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

The best-performing model was identified through comparative evaluation.

---

# 📊 Key Business Insights

* Identified demographic groups with higher infection rates.
* Examined major infection transmission patterns.
* Evaluated patient recovery timelines.
* Compared regional disease impact.
* Investigated factors influencing recovery duration.
* Demonstrated the application of predictive analytics in healthcare.

---

# 💡 Recommendations

* Strengthen surveillance in high-risk regions.
* Improve demographic data quality.
* Enhance contact tracing initiatives.
* Monitor recovery trends across demographic groups.
* Use predictive models to support healthcare planning.

---

# 🚀 Future Enhancements

* Develop an interactive Streamlit dashboard.
* Integrate real-time COVID-19 data sources.
* Explore advanced machine learning algorithms such as XGBoost and LightGBM.
* Build automated reporting pipelines.
* Deploy predictive models as web-based applications.

---

# ▶️ Installation

Clone the repository:

```bash
git clone <repository-url>
```

Navigate to the project directory:

```bash
cd COVID19_Early_Case_Trend_Analysis
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

# 👨‍💻 Author

**Srinath Rajasekar R**

Bachelor of Engineering (Computer Science and Engineering)

Data Analytics | Machine Learning | Python

---

# 📄 MIT License

This project was developed for educational and internship purposes. 
