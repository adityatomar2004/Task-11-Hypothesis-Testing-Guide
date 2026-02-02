# Task 11: A/B Testing - Hypothesis Testing in Python

## Project Overview
This project involves performing a statistical A/B test on a marketing dataset to determine if a new advertisement campaign significantly improves conversion rates compared to a standard PSA (Public Service Announcement).

## Objectives
* [cite_start]Load and clean the marketing A/B testing dataset[cite: 12].
* [cite_start]Define Null ($H_0$) and Alternative ($H_1$) hypotheses[cite: 13].
* [cite_start]Perform a Chi-Square test to determine statistical significance[cite: 15].
* [cite_start]Visualize results and provide data-driven business recommendations[cite: 19, 20].

## Tools Used
* [cite_start]**Primary Tool:** Google Colab[cite: 5].
* [cite_start]**Libraries:** pandas, numpy, scipy, matplotlib, seaborn[cite: 6].

## Statistical Results
* **Control Group (PSA) Conversion Rate:** 1.7854%
* **Test Group (Ad) Conversion Rate:** 2.5547%
* [cite_start]**P-Value:** 0.0000 (Statistically Significant at alpha = 0.05)[cite: 13, 17].

## Final Recommendation
Based on the p-value being less than 0.05, we reject the Null Hypothesis. The advertisement campaign shows a clear, statistically significant lift in conversion rates. [cite_start]I recommend proceeding with the full launch of the ad campaign[cite: 20].

## Repository Contents
* [cite_start]`task11_abtest.ipynb`: Python notebook with full analysis[cite: 22].
* [cite_start]`ab_test_summary.csv`: Summary table of statistical metrics[cite: 23].
* [cite_start]`final_recommendation.txt`: Formal business recommendation[cite: 24].
