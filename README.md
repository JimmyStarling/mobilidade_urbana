# Mobilidade Urbana

Full-version at [Kaggle](https://www.kaggle.com/code/jimmystarling/study-case-for-urban-brazilian-mobility-2010)

## 🔍 Overview
This project analyzes urban mobility trends using public datasets from Brazil. The aim is to identify transportation gaps, predict travel behavior, and support smarter planning.

## 🌍 Business and Societal Relevance
Efficient mobility is central to equity and sustainability. This analysis provides insights for public policy and smarter cities.

## 🧾 Data Description
- Urban mobility survey data
- Municipal census and GTFS feeds
- Raw data from 2010–2020

## 📊 Exploratory Data Analysis
We explore correlations between travel modes, socioeconomic factors, and time of commute across different regions.

## 🧼 Data Cleaning
Custom pipelines were applied to normalize inconsistent data formats and handle missing values using `SimpleImputer`.

## 🤖 Modeling Approach
Classification models (e.g., KNN, Decision Tree) were tested to predict likely transportation choices.

## 📈 Evaluation Metrics
- Accuracy
- Confusion matrix
- Precision/Recall

## 🔑 Key Insights
- Transit accessibility is correlated with income
- Significant gaps exist in low-income neighborhoods

## ▶️ How to Reproduce
```bash
conda env create -f environment.yml
jupyter notebook
