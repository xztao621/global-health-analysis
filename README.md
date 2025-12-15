# 🌍 Global Health Analysis

## Overview
This project analyzes global health indicators for **193 countries from 1990 to 2019**.  
The dataset integrates sources from the **World Bank, WHO, UNICEF, Our World in Data, FAOSTAT**, and **Kaggle**.

The primary goal is to investigate **long-term trends in life expectancy** and evaluate how effectively public health and socioeconomic indicators can predict health outcomes.

---

## 🌐 [Website Presentation](https://xztao621.github.io/global-health-analysis/)
https://xztao621.github.io/global-health-analysis/
A static website was built to present key visualizations and model results.  
Location: `index.html`  
Includes exploratory plots, summary tables, and model outputs.


---

## ❓ Research Questions
- What factors are most strongly associated with long and healthy lives?
- What global health trends emerge when viewed across time and geography?
- How well can public health and socioeconomic indicators predict life expectancy?

---

## 🛠 Methods
The following techniques were used:

- **Exploratory Data Analysis**
  - Scatterplots
  - Line graphs
  - Histograms
  - Boxplots

- **Data Processing**
  - Feature engineering to aggregate related indicators
  - Standardization of numerical variables
  - Removal of columns with **>50% missing values**

- **Modeling**
  - Linear Regression
  - Random Forest
  - XGBoost

Models were trained on **80%** of the data and evaluated on the remaining **20%**.

---

## 📈 Results
Life expectancy exhibits strong relationships with:
- Infant mortality rate
- Birth and death rates
- Income and economic indicators
- Age demographics
- Macronutrient consumption
- Health coverage and access

All models demonstrated strong predictive performance, with **XGBoost achieving the highest accuracy**.

---

## ⚠️ Limitations & Future Work
- Many indicators contained substantial missing data, resulting in the removal of several columns.
- This may introduce bias or exclude relevant health factors.

Future improvements include:
- Incorporating additional indicators with advanced imputation techniques
- Exploring alternative models (e.g., neural networks)
- Performing country- or region-specific analyses

---

## Attribution
*Global Health, Nutrition, Mortality, Economic Data*  
by **Miguel Roca**, via Kaggle  

Licensed under **CC BY-NC-SA 4.0**  
Used for **non-commercial, educational purposes**  
Data has been cleaned and transformed








