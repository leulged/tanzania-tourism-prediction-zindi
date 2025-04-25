# 🌍 Tanzania Tourism Prediction - Zindi Challenge

This project focuses on analyzing and preparing the Tanzania Tourism dataset provided by Zindi. The goal is to perform exploratory data analysis, feature engineering, data cleaning, and manual encoding to make the dataset ready for modeling tourism trends.

---

## 📁 Project Structure

- `Tanzania_Tourism_Prediction.ipynb`: The main notebook containing all analysis and code.
- `train_set.csv`: Training dataset used for EDA and feature engineering.
- `README.md`: Project documentation.

---

## ✅ Objectives

- Explore and clean the data
- Engineer meaningful features
- Aggregate and filter insights
- Encode categorical variables for modeling

---

## 🔧 Tools & Libraries Used

- Python
- Pandas
- NumPy

---

## 📊 Tasks Completed

### 1. Data Exploration
- Counted missing values in each column
- Identified the number of unique values for each categorical column

### 2. Descriptive Statistics
- Calculated average `total_cost` by `purpose`
- Calculated average `night_mainland` and `night_zanzibar` by `country`

### 3. Data Filtering
- Filtered trips with `purpose = Leisure and Holidays` and `total_cost >= 5000`
- Found first-time travelers whose main activity was `Wildlife tourism`

### 4. Feature Engineering
- Created a new column `total_people = total_female + total_male`

### 5. Aggregation & Grouping
- Created `total_nights = night_mainland + night_zanzibar`
- Grouped by `age_group` and calculated mean `total_cost` and `total_nights`
- Counted values of `travel_with`

### 6. Advanced Filtering & Sorting
- Extracted top 10 most expensive trips and their `main_activity`

---

## 🔁 Bonus Tasks

### 7. Data Cleaning
- Replaced `0` values in `total_people` with `NaN`
- Recalculated `cost_per_person`
- Normalized `total_cost` using Min-Max normalization

### 8. Encoding for Modeling
- Factorized `payment_mode` and `travel_with` into numeric codes
- Created binary `has_package` flag based on package-related columns

---

