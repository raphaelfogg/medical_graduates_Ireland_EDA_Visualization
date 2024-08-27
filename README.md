# Medical Graduates Analysis (EDA and Visualization)

Author

Name: Raphael Silva Caetano
Email: raphael.elearning@gmail.com

## Abstract

This project analyzes trends in medical graduates in Ireland from 2016 to 2023, focusing on Pharmacy, Medicine, and Nursing and Midwifery. The aim is to ensure a balance between the supply and demand of healthcare professionals by predicting future graduation trends.

## Introduction

Ireland's education system, particularly in the medical field, plays a vital role in meeting the nation's health needs. This project analyzes graduation trends to help maintain an appropriate balance between the demand for healthcare services and the availability of qualified professionals.

## Objectives

Data Processing and Analysis: Analyze medical graduates data from 2016-2023 in three areas: Pharmacy, Medicine, and Nursing and Midwifery.
Forecasting: Predict graduation trends for the next 5 years using machine learning models.

### Research Questions:

Is there a significant difference in the number of graduates over the years?
What is the gender distribution of graduates in each medical field per year?
Is there a significant difference in the number of male and female graduates across disciplines?
What are the future graduation trends in these medical areas?

## Materials and Methods

### Datasets

CSO Ireland: 7-year historical record of medical graduates.

HEA: Complementary dataset with detailed demographic information.

HSE: Manual extraction of gender demographics data.

### Exploratory Data Analysis (EDA) and Visualization

Libraries: Pandas for data manipulation, Matplotlib for visualization.

Methods: df.head, df.drop, df.rename, df.astype, df.isnull, pd.concat

Visualizations: Bar charts, pie charts, line graphs.

### Statistical Methods

Discrete Distributions: Binomial and Poisson distributions to analyze and predict graduation trends.

Aggregation Functions: df.groupby, .sum, .agg, df.pivot_table


This is an ongoing work. The final analysis will aid educational institutions in planning and resource allocation to meet future healthcare demands effectively.

## References


- Pandas Development Team (2023) Pandas Documentation. Available at: https://pandas.pydata.org/docs/ (Accessed: 29 November 2023).

- SciPy (2023) Available at: https://scipy.org (29 November 2023).

- Towards Data Science (2023) 'What are the plt and ax in matplotlib exactly?'. Available at: https://towardsdatascience.com/what-are-the-plt-and-ax-in-matplotlib-exactly-d2cf4bf164a9 (10 December 2023).

- Tufte, E.R. (2001) The Visual Display of Quantitative Information. 2nd ed. Cheshire, CT: Graphics Press.

