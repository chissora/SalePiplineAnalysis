# SalePiplineAnalysis

## Project Overview
This project analyzes e-commerce pipeline data provided by a portfolio company's CRM (Salesforce). The goal is to derive actionable insights for a new CEO and forecast revenue for 2024. The analysis addresses pipeline health, key growth metrics, ARR changes, seasonality trends, and conversion rates. 

The project delivers:
- Key insights presented in slides.
- An Excel summary table of trends.
- A Python script for exploratory data analysis and forecasting.

## Key Questions Addressed
1. How would you describe the health of new logos (new business) vs. existing customers?
2. What are the growth trends in key metrics (e.g., opportunities, ARR) over time?
3. How does ARR and win rate vary by state?
4. Are there any seasonality trends in the data?
5. How does conversion rate change by lead source?
6. What is the forecasted closed-won revenue for 2024?
7. Are there any data anomalies or hygiene issues?

## Data Description
The dataset includes Salesforce pipeline fields such as:
- **Opportunity ID**: Unique identifier for each deal.
- **Type**: Sales type (e.g., New Business, Renewal).
- **Stage**: Current progress of the deal.
- **Opportunity ARR**: Annual recurring revenue for the opportunity.
- **Billing State/Province**: Billing location.
- **Lead Source**: Origin of the lead.
- **Close Date**: Expected close date.

For a full list of fields and definitions, see the notebook.

## Tools and Libraries
- **Data Analysis**: Pandas, NumPy
- **Visualization**: Matplotlib, Plotly, Seaborn
- **Time Series Analysis**: Statsmodels, PMDARIMA
- **Outlier Detection**: Local Outlier Factor, Z-Score
- **Forecasting**: Auto-ARIMA, Scikit-learn

## Project Workflow
1. **Data Cleaning**: Handling missing values and ensuring data integrity.
2. **Exploratory Data Analysis (EDA)**:
   - Pipeline health by new vs. existing customers.
   - ARR trends by state and seasonality patterns.
   - Conversion rates by lead source.
3. **Forecasting**:
   - 2024 revenue prediction using time series models.
   - Model evaluation with metrics like RMSE.
4. **Anomaly Detection**:
   - Identifying potential data hygiene issues.

## Deliverables
1. **Slides**: Key insights, 2024 revenue forecast, and recommendations.
2. **Excel File**: Summary table highlighting key trends.
3. **Python Script**: Full EDA and forecasting code with detailed comments.
