# REGRESSION PROJECT - 
## TIME SERIES MACHINE LEARNING - The Case of Corporation Favorita

<a name="readme-top"></a>

<div align="center">
  <br/>

  <h3><b>Time Series Analysis and Favorita Store sales prediction</b></h3>

</div>

#  Table of Contents

- [REGRESSION PROJECT - The Case of Favorita Stores]
(#REGRESSION-PROJECT---The-Case-of-Favorita-Stores-)
- [ Table of Contents](#-table-of-contents)
- [ \[Analyze and Predict Store Sales\] ](#-Analyze-and-Predict-Store-Sales-)
    - [Summary ](#summary-)
    - [ Project Description ](#-project-Description-)
    - [Objectives of Project](#-objective-of-Project-)
    - [Goal of Project](#-goal-of-Project-)
    - [ Data ](#-data-)
    - [ Hypothesis ](#-hypothesis-)
        - [ Conclusion on hypothesis](#-conclusion-on-hypothesis-)
    - [ Research Questions ](#-research-Questions-)
    - [ Installation ](#-installation-)
    - [ Author ](#-author-)
    - [ License ](#-license-)


-  *Attached are articles to my project with more information.*
## Summary
| Article     | Links      | Description |
|-----------|-------------|:-------------:|
|Power BI| https://app.powerbi.com/view?r=eyJrIjoiMTE3MmM2MTctN2FhZi00MmI0LWE1NzktMzRkY2M4YWJiY2ZjIiwidCI6IjQ0ODdiNTJmLWYxMTgtNDgzMC1iNDlkLTNjMjk4Y2I3MTA3NSJ9 |  [Interactive dashboard](/) |
|Medium   | https://medium.com/@phinmaiyo/analysis-of-external-factors-that-impact-sales-of-a-retail-store-a-regression-analysis-f7445bbf3e86                         |  [ Best article to gain machine-learning insights                        ](/) |


## Project Description <a name="project-description"></a>
This project looks at regression models where a model is trained on a dataset in order to make predictions and forecast. The main goal of regression analysis is to underwstand how changes in the independent variables are associated with changes in the dependent variable. 
Time Series machine learning also referred as time series forecasting is the application of machine learning techniques to analyze and predict time series data. Time series data consists of observations collected or recorded at successive points in time, making it essential in various fields. Machine learning models can be particularly useful in extracting patterns, making predictions, and uncovering insights from time series.  

## Objectives of Project <a name="objectives-of-project"></a>
1. Learn more about time series models and predict sales data for Corporation Favorita, a large Ecuadorian-based grocery retailer. 

## Goal of Project <a name="goal-of-project"></a>
Build a model that more accurately predicts the unit sales for thousands of items sold at different Favorita stores

## Data <a name="data"></a>
The datasets where extracted from three(3) places. 

* First dataset - Three (3) tables(Crude oil prices, holiday events, and stores) were extracted from Microsoft SQL Server
* Second dataset - Two (2) tables(sampel_submission, and test) were downloaded from OneDrive
* Third dataset - Two(2) tables (train and transactions) were downloaded from a GitHub Repository

## Hypothesis <a name="hypothesis"></a>
* H_o: Promotions have no significant effect on product sales.
* H_a: Promotions positively impact product sales, leading to increased sales during promotional periods

### Conclusion on hypothesis <a name="conclusion-on-hypothesis"></a>
We reject the null hypothesis and conclude that promotions has significant effect on sales

## Research Questions <a name="research-questions"></a>
1. What is the effect of seasonal variations (e.g., Monthly, or quarterly patterns) on total sales?

2. What store is the highest performer in terms of sales?

3. What are the best-selling products per location?

4. Does store size affect total sales?

5. Which days have the most sales?

## Installation: <a name="installation:"></a>
* pyodbc  
* python-dotenv
* openpyxl
* missingno
* scikit-learn
* pmdarima
* statsmodels

## Author <a name="author"></a>
Phonex Chemutai
- GitHub: [@phinmaiyo](https://github.com/phinmaiyo/)
- LinkedIn: [Phonex Chemutai](https://www.linkedin.com/in/phonex-chemutai/)