# Customer Segmentation & Retention Strategy

## Project Objective

This project segments customers using Recency, Frequency, and Monetary (RFM) analysis combined with behavioral signals such as support activity, campaign engagement, and website usage.

## Files

### rfm_segmentation.ipynb

Contains:

* Data loading
* RFM feature engineering
* Customer segmentation logic
* Behavioral analysis
* Segment visualizations

### segments.csv

Contains:

* customer_id
* assigned segment
* recency, frequency, monetary metrics
* support and engagement indicators

### retention_strategy.md

Business recommendations for each segment.

### manual_review_cases.md

Edge-case customers requiring human review.

## Key Findings

* Overall churn rate: 46.96%
* Hibernating customers exhibit the highest churn risk (77.96%)
* Champions exhibit the lowest churn risk (2.34%)
* Recency is the strongest predictor of churn

## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab
