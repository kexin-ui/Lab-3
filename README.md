# Lab 3 — One-Way ANOVA Test (Sweden)

## Student Name:
Your Name

## Course:
Statistical Data Analytics

## Objective

The objective of this project is to demonstrate the application of a One-Way Analysis of Variance (ANOVA) test using the World Energy dataset.

The analysis investigates whether electricity demand in Sweden differs significantly across decades.

---

## Dataset

WorldEnergy.csv

The dataset contains historical information on:

- Electricity demand
- Population
- GDP
- Electricity generation
- Energy imports
- Energy share

---

## Methodology

The following steps were performed:

1. Load dataset
2. Filter Sweden data
3. Create decade variable
4. Handle missing values
5. Calculate descriptive statistics
6. Visualize data using boxplot
7. Check homogeneity of variance using Levene Test
8. Perform One-Way ANOVA
9. Conduct Tukey HSD post-hoc test

---

## Hypothesis

Null Hypothesis (H0):

There is no significant difference in electricity demand between decades.

Alternative Hypothesis (H1):

There is a significant difference in electricity demand between decades.

---

## Result

The ANOVA test produced a p-value less than 0.05.

Therefore:

The null hypothesis was rejected.

This indicates that electricity demand in Sweden differs significantly across decades.

---

## Libraries Used

- pandas
- matplotlib
- seaborn
- statsmodels
- scipy
