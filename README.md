# 🧠 Stroke Prediction Dataset - Exploratory Data Analysis (EDA)

This repository contains exploratory data analysis performed on a healthcare dataset focused on predicting the likelihood of a stroke based on various health and demographic attributes.

---

## 📁 Dataset Overview

- **Source**: [`healthcare-dataset-stroke-data.csv`](./healthcare-dataset-stroke-data.csv)
- **Rows**: 5,110  
- **Columns**: 12  
- **Target Variable**: `stroke` (1 = stroke, 0 = no stroke)

---

## 📌 Columns Summary

| Column             | Type     | Description                                  |
|--------------------|----------|----------------------------------------------|
| `id`               | int      | Unique identifier                            |
| `gender`           | object   | Gender of the patient                        |
| `age`              | float    | Age of the patient                           |
| `hypertension`     | int      | 0 = no, 1 = has hypertension                 |
| `heart_disease`    | int      | 0 = no, 1 = has heart disease                |
| `ever_married`     | object   | Marital status                               |
| `work_type`        | object   | Type of employment                           |
| `Residence_type`   | object   | Urban or Rural                               |
| `avg_glucose_level`| float    | Average glucose level                        |
| `bmi`              | float    | Body mass index                              |
| `smoking_status`   | object   | Smoking habits                               |
| `stroke`           | int      | Target column (0 = no stroke, 1 = stroke)    |

---

## 🔍 Exploratory Data Analysis Highlights

### ✅ Missing Value Check
- Missing values detected in `bmi`: **201 missing entries**

