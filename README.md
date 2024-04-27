# S-Mobile: Predicting Customer Churn

This project explores predictive modeling to forecast customer churn for S-Mobile, a leading cellphone carrier in Singapore. The objective is to develop a proactive churn management strategy that identifies customers at risk of churning before they leave, allowing for targeted actions to retain them.

## Project Background
Shu Ying Seng, a former call center retention manager at S-Mobile and a graduate of the National University of Singapore's Master’s in Business Analytics program, leads the analytics team tasked with reducing customer churn. The goal is to use existing data to predict customer churn and develop targeted offers and incentives to retain at-risk customers.

## Project Goals
The key tasks outlined for this project are:
1. **Develop a Predictive Model**: Use various modeling techniques, including logistic regression, to predict customer churn.
2. **Identify Churn Drivers**: Determine the main factors that drive customer churn using Variable Importance (Permutation Importance) and Partial Dependence plots.
3. **Develop Retention Strategies**: Based on churn drivers, create targeted actions, offers, and incentives to reduce churn.
4. **Quantify Impact on Churn**: Predict the effect of retention strategies on the probability of churn and propose experimental setups to measure impact.
5. **Targeting Strategy**: Decide which actions, offers, or incentives to use for different customer segments.
6. **Evaluate Economics**: Conduct a profitability analysis for retention strategies over a 5-year (60-month) time window, focusing on Customer Lifetime Value (CLV).

## Data Description
The project uses a dataset with customer information and behavior over a 4-month period, with an additional 30-day churn response variable. The dataset consists of:
- **Training Sample**: 27,300 observations with a 50% churn rate.
- **Test Sample**: 11,700 observations with a 50% churn rate.
- **Representative Sample**: 30,000 observations with a 2% churn rate, reflecting S-Mobile's actual monthly churn rate.

Additionally, a larger dataset with 1 million rows is available for re-estimating models and generating predictions for the representative sample.

## Methodology
The project employs a variety of machine learning techniques, with a focus on logistic regression, to develop a predictive churn model. The team uses the training data to build models and the test data to validate them. Insights from the models guide the development of retention strategies.

## Outcomes and Insights
The project aims to identify the most effective actions, offers, or incentives to reduce churn and improve customer retention. By targeting at-risk customers, S-Mobile hopes to achieve better retention rates, increased customer satisfaction, and improved profitability.

