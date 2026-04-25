# House-Price-Analysis-Bangalore-Dataset

## Overview
This project analyzes the Bangalore house price dataset with a focus on **price per square foot**. The goal is to perform exploratory data analysis (EDA), detect and handle outliers using multiple statistical techniques, analyze data distribution, and study relationships between variables.

---

## Dataset
Download the dataset from the link below:

https://drive.google.com/file/d/1UlWRYU0UglE2ex3iFse0J6eCLEU8g98P/view?usp=sharing

---

## Objectives

- Perform basic Exploratory Data Analysis (EDA)  
- Detect and remove outliers using:
  - Mean and Standard Deviation  
  - Percentile Method  
  - Interquartile Range (IQR)  
  - Z-Score Method  
- Visualize outliers using box plots  
- Analyze distribution using histogram and apply transformations  
- Compute correlation and visualize using a heatmap  
- Analyze relationships using scatter plots  

---

## Tech Stack

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- SciPy  

---

## Project Workflow

### 1. Exploratory Data Analysis
- Loaded dataset and examined structure  
- Checked missing values  
- Generated summary statistics  
- Created **price_per_sqft** feature  

---

### 2. Outlier Detection

#### Mean & Standard Deviation
- Defined range: mean ± 3 * standard deviation  
- Removed values outside the range  

#### Percentile Method
- Removed values below 5th percentile and above 95th percentile  

#### Interquartile Range (IQR)
- Calculated Q1 and Q3  
- Removed values outside:
