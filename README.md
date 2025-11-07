# 🧠 Non-Parametric Analysis of Mental-Health Data

This project presents an in-depth **non-parametric statistical analysis** of a mental-health survey dataset.  
The study explores the relationship between various psychological and demographic factors such as **depression, anxiety, academic pressure, sleep quality, and residential status**, using robust, assumption-free statistical methods.

---

## 📊 Overview

The primary objective of this project is to:
- Understand the **distribution of mental-health indicators** among students.
- Compare psychological parameters across different **genders**, **residential statuses**, and **academic environments**.
- Apply **non-parametric statistical tests** where assumptions of normality and homogeneity of variance are violated.

---

## 📁 Dataset

The dataset used is publicly available on Kaggle:

🔗 [Student Mental Health Survey](https://www.kaggle.com/datasets/abdullahashfaqvirk/student-mental-health-survey)

It contains self-reported responses from students regarding their **mental health**, **academic stress**, and **daily habits**.

---

## 🧮 Methodology

### 1. **Exploratory Data Analysis (EDA)**
- Summary statistics and visualizations to understand variable patterns.  
- ECDF (Empirical Cumulative Distribution Function) plots for depression and anxiety scores.  
- Boxplots, histograms, and violin plots to assess spread and variation.

### 2. **Statistical Tests Used**
| Test | Purpose | Example |
|------|----------|----------|
| **Mann-Whitney U Test** | Compare two groups | Depression vs Gender |
| **Kruskal-Wallis Test** | Compare more than two groups | Academic pressure vs Residential status |
| **Anderson-Darling k-sample Test** | Compare multiple distributions | Sleep quality across departments |
| **Spearman Rank Correlation** | Measure non-linear associations | Depression and academic pressure |

### 3. **Tools & Environment**
- **R** (version ≥ 4.3)
- **RStudio** IDE
- Libraries: `ggplot2`, `dplyr`, `readr`, `PMCMRplus`, `nortest`, `DescTools`, `qpdf`

---

## 🖼️ Visualizations

Key plots included:
- ECDF of depression and anxiety by gender  
- Distribution plots for academic pressure  
- Correlation heatmaps for psychological measures  
- Boxplots comparing depression across residential status  

All plots were generated using **ggplot2** with a minimalist and publication-ready aesthetic.

---

## 📈 Results Summary

- **Depression** and **anxiety** levels showed **no significant gender difference** (Mann-Whitney U Test, p > 0.05).  
- **Academic pressure** was **significantly different** across **residential statuses** (Kruskal-Wallis, p < 0.05).  
- Moderate **positive correlation** between **academic pressure and depression**.  
- Non-normal distributions confirmed by **Shapiro-Wilk test** and **ECDF plots**.

---

## 📜 File Structure

