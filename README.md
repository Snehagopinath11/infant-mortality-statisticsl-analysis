# infant-mortality-statistical-analysis

Statistical Analysis of Infant Mortality: A Time Series and Cluster Approach

📌 Project Overview

This project analyzes infant mortality rates using statistical methods. It consists of two major components: time series analysis of India's infant mortality rate and cluster analysis of infant mortality rates across countries.

The study uses data from the World Bank Open Data portal to examine historical trends, forecast future infant mortality rates, and identify groups of countries with similar infant mortality patterns.

🎯 Objectives

Time Series Analysis

- To analyze India's Infant Mortality Rate (IMR) from 1971 to 2024.
- To identify an appropriate ARIMA model.
- To validate the fitted model using diagnostic tests.
- To forecast India's infant mortality rate for the next 10 years.

Cluster Analysis

- To group countries based on infant mortality rates from 2020 to 2024.
- To determine the optimal number of clusters using the Elbow Method.
- To perform hierarchical clustering using Ward's method.
- To apply K-means clustering and interpret the resulting groups.

📊 Project Methodology

1. Time Series Analysis

Study period: India, 1971–2024

Statistical techniques used:

- Time series visualization
- Augmented Dickey-Fuller (ADF) test
- KPSS test
- Differencing
- Autocorrelation Function (ACF)
- Partial Autocorrelation Function (PACF)
- ARIMA model selection using AIC and BIC
- Ljung-Box test for residual diagnostics
- 10-year forecasting

Selected model: ARIMA(2,2,2)

2. Cluster Analysis

Study period: 2020–2024

Techniques used:

- Elbow Method
- Hierarchical clustering using Ward's method
- K-means clustering
- Cluster interpretation

The analysis identifies three broad groups of countries based on their infant mortality patterns: high, moderate, and low infant mortality.

🛠️ Tools and Technologies

- R Programming — Statistical analysis and modeling
- Time Series Analysis — ARIMA modeling and forecasting
- Cluster Analysis — Hierarchical and K-means clustering
- Data Visualization — Time series plots, ACF/PACF plots, scree plots, dendrograms, and residual plots

📂 Project Structure

infant-mortality-time-series-clustering/
├── README.md
├── report/
│   └── final_project_report.pdf
├── code/
│   ├── time_series_analysis.R
│   └── cluster_analysis.R
├── data/
│   ├── IMR.csv
│   └── imrdata.xlsx
└── results/
    └── plots/

Note: Add the data files and R scripts only when the actual files are available in your repository.

📈 Key Findings

- India's infant mortality rate shows a long-term declining trend over 1971–2024.
- The ARIMA(2,2,2) model was selected for the 10-year forecast in the report.
- The country-level analysis identified three broad clusters.
- The clusters represent high, moderate, and low infant mortality patterns.
- The findings highlight differences in infant mortality outcomes across countries.

📚 Data Source

World Bank Open Data — Infant Mortality Rate

https://data.worldbank.org/indicator/SP.DYN.IMRT.IN

The Infant Mortality Rate is measured as the number of deaths of infants under one year of age per 1,000 live births.

👩‍🎓 Project Details

- Author: Snehagopinath C
- Programme: Master of Science in Statistics
- Institution: University of Mysore
- Project Date: June 2026

📝 Conclusion

This project demonstrates the application of statistical techniques to public health data. Time series analysis is used to study historical trends and forecast India's infant mortality rate, while cluster analysis groups countries according to their infant mortality patterns.

The study illustrates how statistical modeling can help understand changes in infant mortality and differences in child health outcomes across countries.
