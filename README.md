# AadhaarLens-Activity-Analysis-EDA-Public

# AadhaarLens: Where Does Aadhaar Activity Actually Happen? 🔍

## 📌 Project Overview

AadhaarLens is a data analytics project that analyzes UIDAI Aadhaar enrolment and update data to understand service demand patterns across age groups, geography, and time.

The project focuses on identifying where Aadhaar activity is concentrated and understanding the difference between enrolment and update-related demand.

---

## 🎯 Problem Statement

**AadhaarLens: Where Does Aadhaar Activity Actually Happen?**

To identify Aadhaar service demand patterns across time, age groups, and geography, and understand whether regions show stronger enrolment demand or update and maintenance demand.

---

## 🛠️ Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔄 Project Workflow

The project followed the following steps:

### 1. Data Understanding
- Examined dataset structure and columns
- Checked data types
- Understood enrolment and update-related variables

### 2. Data Cleaning
- Removed unnecessary columns
- Checked missing values
- Checked duplicate records
- Converted date column to datetime format
- Examined outliers

### 3. Feature Engineering

Created the following new features:

- Total Enrolment
- Total Demographic Updates
- Total Biometric Updates
- Total Updates
- Total Aadhaar Activity

### 4. Exploratory Data Analysis

Performed:

#### Univariate Analysis
- Analysed overall Aadhaar service demand
- Analysed enrolment across different age groups

#### Bivariate Analysis
- Identified states with the highest Aadhaar activity
- Compared enrolment and update demand across states
- Analysed Aadhaar activity patterns over time

#### Multivariate Analysis
- Used a correlation heatmap to understand relationships between different Aadhaar enrolment and update activities

---

## 📊 Key Focus Areas

The analysis explores:

- Aadhaar service demand
- Age-wise enrolment patterns
- Geographic distribution of activity
- Enrolment vs update demand
- Activity trends over time
- Relationships between different Aadhaar services

---

## 📁 Project Structure

```text
AadhaarLens/
│
├── data/
│   └── Aadhaar_Data.csv
│
├── notebooks/
│   └── AadhaarLens_EDA.ipynb
│
├── README.md
│
└── requirements.txt
