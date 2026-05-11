 Exploratory Data Analysis (EDA) - Project 2

## Project Overview

This project focuses on Exploratory Data Analysis (EDA) as part of the DecodeLabs training program. The objective was to move beyond basic reporting by interrogating a dataset to identify hidden patterns, trends, and data quality issues.

## Technical Tools

* **Language:** Python
* **Libraries:** Pandas, Seaborn, Matplotlib
* **Environment:** Jupyter Notebook (Anaconda)

## Key Findings

* **Data Integrity:** Identified **107 Calculation Errors** where the product of Quantity and Unit Price did not match the Total Price, indicating data corruption.
* **Handling Missing Values:** Cleaned the `CouponCode` column to ensure a complete dataset for analysis.
* **Descriptive Statistics:** - Established a **Five-Number Summary** (Minimum, Q1, Median, Q3, Maximum) to create a statistical skeleton of the data.
* Compared the **Mean and Median** to determine the influence of outliers on the average values.

  Distribution Analysis: Used histograms and KDE plots to determine the "Shape of Evidence," identifying whether the data followed a Symmetrical or Skewed distribution.

## Implementation Steps

1. Load the dataset using Pandas `read_excel`.
2. Diagnose data quality by checking for null values and calculation inconsistencies.
3. Generate statistical summaries using `df.describe()`.
4. Visualize distributions and outliers using Seaborn.
5. Document insights to provide decision support.

## Conclusion

This analysis serves as a vital bridge toward professional data development, proving the ability to transform raw, static tables into meaningful, actionable insights.
