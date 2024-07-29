Analyzing Charging Efficiency Ratios of Electric Vehicles
Project Overview
This project aims to analyze and compare the charging efficiency ratios of two different electric vehicles, the Mitsubishi Outlander and the BMW iXDrive 50, using real-world charging data. The goal is to determine if there is a statistically significant difference in their efficiency ratios and to provide insights into their performance on electrical distribution networks.

The analysis is conducted using a Jupyter Notebook, where data from an Excel file is loaded and pre-processed for statistical analysis. Normality checks, variance tests, and a two-sample t-test are performed to ensure the reliability of the comparisons and to identify significant differences.

Key Features
Data Sources: Utilizes real-world charging data for the Mitsubishi Outlander and BMW iXDrive 50. - Obtained from Dataverse Harvard
Analysis: Normality checks using the Shapiro-Wilk test, variance tests using Levene's test, and a two-sample t-test to compare efficiency ratios.
Tools: Analysis performed using Python and Jupyter Notebook.
Methodology
Data Collection: Efficiency ratio data for Mitsubishi Outlander and BMW iXDrive 50.
Normality Check: Shapiro-Wilk test to assess the normality of the data distributions.
Variance Testing: Levene's test to check for equal variances between the two groups.
Statistical Testing: Two-sample t-test to compare the means of efficiency ratios and assess statistical significance.
Visualization: T-distribution plot with the test statistic.
Findings
Shapiro-Wilk Test for Normality: Assessed the normality of the efficiency ratio distributions for both vehicles.
Levene's Test for Equal Variances: Checked if the variances between the two groups are equal.
Two-Sample t-Test:
t-statistic and p-value calculated to determine the significance of differences.
Visualization of the t-distribution with the test statistic.
Conclusion
The study provides a detailed comparison of the charging efficiency ratios between the Mitsubishi Outlander and BMW iXDrive 50. By using rigorous statistical tests, the analysis offers insights into whether there are significant differences in their charging efficiencies, which can contribute to understanding their impact on electrical distribution networks.

Future Work
Future research could include:

Alternative Statistical Methods: To account for any deviations from normality and enhance the robustness of the analysis.
Granular Analysis: Investigating other factors affecting charging efficiency and their direct impacts on specific aspects of electrical grid performance. (Waveforms, tempature, area, etc.)
