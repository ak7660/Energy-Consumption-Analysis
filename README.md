# 🌍 Global Energy Consumption Analysis

This project investigates global energy consumption patterns across 294 countries using a large and complex dataset from **Our World in Data**. The study uses **exploratory data analysis (EDA)** and **regression modeling** to answer five key research questions linking energy use to population, GDP, and renewable trends.

## 📌 Project Objectives

* Clean and filter high-dimensional, sparse data for meaningful analysis
* Visualize global and country-specific energy consumption trends
* Build regression models to examine links between GDP, population, and energy use
* Evaluate model diagnostics and multicollinearity
* Identify significant insights about energy demand and development

## 🔍 Research Questions

1. How has global energy consumption changed over time?
2. Is there a relationship between population and energy use?
3. Does higher GDP always imply higher energy consumption?
4. Do rapidly growing populations increase energy demand?
5. How have energy trends changed for the world’s top GDP countries?

## 📊 Methods Used

* Data cleaning and transformation via R scripts
* EDA with log-scale plots, correlation matrices, and time-series graphs
* Simple and multiple linear regression (with log transformations)
* Diagnostics and variance inflation factor (VIF) analysis
* Cohen’s *d* effect size comparisons for GDP vs. energy usage

## 📁 Key Files

* `report.Rmd`: Full report with all models, plots, and interpretations
* `eda.Rmd`: Exploratory data analysis code
* `Energy_Consumption.rmd`: Linear regression and diagnostics
* `pre_analysis.rmd`, `filter_doc.rmd`: Data preprocessing and filtering utilities

## 📌 Highlights

* Log-transformed models revealed strong links between **GDP and energy usage** (R² = 0.89)
* Population and energy consumption are significantly correlated (MLR R² ≈ 0.84)
* Renewable energy trends vary widely across top economies
* Found limitations in scaling and heteroscedasticity in lower-GDP countries
* Identified countries with anomalous energy usage behavior

## 📎 Resources

* 📊 Dataset: [Our World in Data - Energy](https://ourworldindata.org/energy)
* 📘 Codebook: [OWID Energy Codebook](https://github.com/owid/energy-data)

---
