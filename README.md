# Marketing-Campaign-Response-Analysis

## [View Full Analysis](https://rpubs.com/annboo/1438285). Link to the RPub with the html file of the project. 
## [Interactive dashboard summarising key findings](https://rpubs.com/annboo/1438331)

## Overview
An exploratory and predictive analysis of customer  responses to a marketing campaign, using a real-world 
dataset of 2,240 customers. The project combines hypothesis-driven statistical testing with a  decision tree model to identify the key drivers  of campaign acceptance and produce actionable targeting recommendations.

## Research Questions
1. Does day of week affect campaign response?
2. Does income level predict campaign response?
3. Does purchase channel (web vs. in-store) affect response?
4. Does recency of last purchase affect response?

## Methods
- Chi-square tests for categorical variables
- T-tests for continuous variables
- Decision tree classifier (rpart) with class weighting to address imbalance
- ROC curve and AUC for model evaluation
- Train/test split (80/20) for out-of-sample model validation

## Key Findings
| Predictor | Finding |
|--------|---------|
| Income | Strongest predictor: above average income customers significantly more likely to respond |
| Recency | Recently active customers show higher response rates, especially among below average income |
| Web purchases | Significant positive relationship with response - digital engagement is a key behavioural signal |
| In-store purchases | No significant relationship with response |
| Day of week | No significant effect — campaigns can launch any day |

## Business Recommendations
- Prioritise above-average income segment in targeting
- Build re-engagement flows for recently active users
- Focus campaign spend on digitally active customers

## Files
- `Project - Marketing Campaign Response Analysis.Rmd` — full report with all statistical tests, visualisations and findings
- `Dashboard.Rmd` — code with interactive dashboard summarising key findings


## Dataset
Kaggle Marketing Analytics dataset  
[Source](https://www.kaggle.com/datasets/jackdaoud/marketing-data/data)
2,240 customers and 29 variables

## Skills Demonstrated
R · Hypothesis testing · Statistical analysis · 
Predictive modelling · Data visualisation · 
Business insight communication 
