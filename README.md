# Virtual Construction Business Intelligence

## Project Overview

This project demonstrates an end-to-end business intelligence workflow for analyzing construction project costs, physical progress, financial progress, schedule extensions, and cost-overrun risks.

The project uses Power BI for interactive reporting and Python for predictive analytics.

## Objectives

* Analyze construction project performance using KPIs.
* Prepare and transform project data.
* Build a structured Power BI data model with DAX measures.
* Develop interactive dashboards for project monitoring.
* Evaluate a Linear Regression model for cost-overrun estimation.
* Identify analytical limitations and recommend improvements.

## Tools and Technologies

* Microsoft Power BI
* Power Query
* DAX
* Python
* Pandas and NumPy
* Scikit-learn
* Google Colab

## Project Components

1. Strategic planning and KPI selection
2. Data sourcing and transformation
3. Data modeling and DAX calculations
4. Interactive dashboard development
5. Predictive analytics and model evaluation
6. Final performance evaluation

## Predictive Model Results

The Linear Regression model was evaluated against a mean-prediction baseline.

| Metric    | Linear Regression |            Baseline |
| --------- | ----------------: | ------------------: |
| MAE       |      176.02 crore |        195.70 crore |
| RMSE      |      304.65 crore |        333.02 crore |
| R-squared |             0.163 | Approximately 0.000 |

The model performed better than the baseline on the test set, but its predictive power was limited. Its estimates should be treated as preliminary rather than reliable forecasts.

## Key Limitations

* The dataset contains 500 project-level records.
* The `Primary_Bottleneck` column contains missing values.
* The data does not provide a complete historical time series.
* Predictive model performance requires further improvement and validation.

## Disclaimer

This project is intended for learning and portfolio demonstration. The model estimates do not guarantee actual construction costs or future project outcomes.
