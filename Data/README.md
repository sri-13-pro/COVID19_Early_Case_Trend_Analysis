# Data Directory

## Overview

This directory contains all datasets used throughout the **COVID-19 Early Case Trend Analysis & Recovery Insights** project.

The data is organized into separate folders for raw and processed datasets to ensure reproducibility and maintain data integrity throughout the analytics workflow.

---

## Directory Structure

```text
data/
│
├── raw/
│   └── patient.csv
│
└── processed/
    └── cleaned_patient_data.csv
```

---

## Raw Data

### `patient.csv`

This folder contains the original patient-level COVID-19 dataset received for analysis.

The raw dataset remains unchanged and serves as the primary data source for the project.

Typical attributes include:

* Patient ID
* Sex
* Birth Year
* Country
* Region
* Infection Reason
* Infection Order
* Contact Number
* Confirmed Date
* Released Date
* Deceased Date
* Patient State

---

## Processed Data

### `cleaned_patient_data.csv`

This dataset is generated after performing data cleaning and feature engineering.

Processing steps include:

* Handling missing values
* Removing duplicate records
* Converting date columns
* Creating Age feature
* Creating Age Group feature
* Calculating Recovery Duration
* Standardizing categorical values

This processed dataset is used for:

* Exploratory Data Analysis (EDA)
* Statistical Analysis
* Hypothesis Testing
* Machine Learning
* Business Insights

---

## Data Workflow

```text
Raw Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
Processed Dataset
      │
      ▼
EDA
      │
      ▼
Statistical Analysis
      │
      ▼
Machine Learning
```

---

## Notes

* Do not modify files inside the `raw/` directory.
* All transformations should be performed programmatically within the notebook or source code.
* Generated datasets should be stored only in the `processed/` directory to preserve the original data.

---

