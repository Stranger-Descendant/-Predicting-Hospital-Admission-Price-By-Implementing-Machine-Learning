# -Predicting-Hospital-Admission-Price-By-Implementing-Machine-Learning

Project Member: 

![Hospital Cover](https://github.com/Stranger-Descendant/-Predicting-Hospital-Admission-Price-By-Implementing-Machine-Learning/raw/main/hospital%20cover.jpeg)


## Table of Contents

- [Introduction](#Introduction)
- [Data](#Data)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Baseline Model](#Baseline-Model)
- [Optimization Model](#Optimization-Model)
- [Results and Analysis](#results-and-analysis)
- [Business Insights](#Business-Insights)
- [References](#References)

## Introduction

This project aims to implement advanced machine learning techniques to accurately predict hospital billing costs for patients. By analyzing various patient data and health metrics, the model seeks to enhance financial planning and decision-making for healthcare providers.

## Data

The dataset used consists of 2,772 entries across 7 columns, focusing on individual medical costs billed by health insurance. Key variables include age, sex, BMI, number of children, smoking status, region, and charges. The dataset contains categorical features (e.g., sex, smoker, region) and continuous variables (e.g., age, BMI, charges).

## Exploratory Data Analysis

- Descriptive Statistics: Initial analysis reveals insights into demographics, showing a higher prevalence of younger individuals, lower smoking rates, and an even distribution across regions.
- Visualizations: Various plots (histograms, box plots, and heatmaps) illustrate the distribution of demographic characteristics and their correlation with medical charges, highlighting significant relationships between smoking status, age, BMI, and charges.

## Baseline Model

- Preprocessing: Categorical features are encoded using one-hot encoding, while numerical features remain unchanged. The dataset is split into training and testing sets for model evaluation.
- Model Selection: Several regression models are implemented, including Linear Regression, Random Forest, and XGBoost, to predict continuous insurance charges.


## Optimization Model

- Training and Evaluation: Models are trained, and metrics such as R² score, Mean Squared Error (MSE), and Mean Absolute Error (MAE) are calculated to assess their performance. The "Extra Trees Regression" model emerges as the best performer.
- Classification Models: The continuous charges variable is transformed into a binary category (above/below median), allowing for classification. Logistic Regression and XGBoost Classification yield the highest accuracies.

## Results and Analysis

![result](images/result.png)

The figure shows the optimal warehouse and freight allocation for each of the 1000 orders. Note that freight allocation is composed of a warehouse port and carrier.

Total cost reduction:

- The optimal cost of our solution is **\$5,365,566.57**.
- The cost of the solution produced by the baseline model is **\$8,878,241.89**.
- Our solution reduced the total cost by **\$3,512,675.32**, which is a **39.5%** reduction in cost.

## Business Insights

The solution produced by our model surpasses the previously provided solution by the freight company.

- We reduced the total cost, including storage and transportation costs, by **39.5%**.

The outcomes obtained in our study align with the expectations derived from our preliminary exploratory analysis.

- Many orders to pass through warehouse port 4.
- Due to their lower daily cost per unit, many orders were allocated to Warehouse three and 11.
- Few orders are allocated to warehouses 15, 16, or 18 due to their high daily cost.

## References
