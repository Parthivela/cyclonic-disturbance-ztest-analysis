# cyclonic-disturbance-ztest-analysis
Hypothesis testing on historical cyclonic disturbance data using one-tailed Z-test and visualizations.

Project Overview
This project performs a statistical analysis of historical cyclonic disturbance data to test hypotheses regarding changes or patterns in the frequency or intensity of cyclones over time. Using a one-tailed Z-test, we assess whether there is statistically significant evidence to support a specific directional claim (e.g., increase in the number of cyclonic disturbances in recent years compared to historical averages).

The analysis includes:
Data preprocessing and exploratory data analysis (EDA) on the historical cyclonic dataset.
Formulation of null and alternative hypotheses tailored to the research question.
Calculation of the Z-statistic and corresponding p-value using a one-tailed Z-test.
Visualization of the data distribution, test statistics, and confidence intervals to support the hypothesis testing.
Interpretation of the results in the context of climatic or environmental trends.

Dataset Description
The dataset consists of historical records of cyclonic disturbances, including:
Date and year of occurrence
Intensity measures (e.g., wind speed, pressure)
Frequency counts per year or season
Other relevant meteorological parameters

Objectives
To determine if there has been a significant increase/decrease in the number or intensity of cyclonic disturbances over a given period.
To provide visual insights into the trends and variations in cyclonic activity.
To demonstrate the application of hypothesis testing using a one-tailed Z-test in environmental data analysis.

Methodology
Hypothesis Formulation:
Null hypothesis (H0): There is no increase (or decrease) in the mean frequency/intensity of cyclonic disturbances.
Alternative hypothesis (H1): There is an increase (or decrease) in the mean frequency/intensity of cyclonic disturbances.

Data Preparation:
Cleaning and structuring historical cyclonic data.
Calculating sample statistics: mean, standard deviation, and sample size.
Conducting the One-Tailed Z-Test:
Compute the Z-statistic based on sample mean, population mean, population standard deviation, and sample size.
Determine the critical value and p-value for the chosen significance level (e.g., α = 0.05).

Visualization:
Histograms or KDE plots to show data distribution.
Line plots to visualize trends over years.
Z-distribution curve highlighting critical region and test statistic.
Confidence interval plots to show the range of plausible values for the mean.

Conclusion:
Decision on hypothesis acceptance or rejection.
Interpretation of statistical and environmental implications.

Tools & Libraries
Python (Pandas, NumPy)
SciPy (for statistical tests)
Matplotlib / Seaborn (for visualizations)


