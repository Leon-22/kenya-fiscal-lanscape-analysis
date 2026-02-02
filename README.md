# Kenya Public Debt & Economic Analysis(2000-2021)
## Project Overview
This project provides a data driven evaluation of Kenya's Fiscal Trajectory over the last 25 year. By intergrating datasets on Public Debt stock, Interest Payments and Annual GDP.


The primary goal is to determine the "Effective Interest Rate" of domestic versus foreign debt and assess Kenya's debt Sustainability against
regional benchmarks like the East African Community (EAC) 60% Debt-to-GDP threshold.

## Key Insights
1. Rising Servising Costs: Interest Payments Acceleration and high cost of domestic debt servising.
   
  ![Effective Interest Rate: Domestic vs External Borrowing](Images/interest_rate.png)
  
3. Sustainability Benchmark: Track the Debt to GDP ratio from 2000 to 2021
   
  ![Debt-to-GDP Ratio](Images/debt_to_gdp.png)

## Tech Stack
Python
Libraries: Pandas for Data Cleaning
           Matplotlib & Seaborn for Time-series visualization and trend analysis.

## Data Sources
1. Public Debt (Ksh Million): Monthly historical data on domestic and external debt stocks.
2. Interest Payments: Monthly breakdown of interest paid on domestic and foreign obligatations.
3. Annual GDP: Yearly figures for Nominal GDP, Real GDP and GDP Growth rates.

## Feature Engineering
To move beyond raw data the following metrics were engineered:
1. Effective Interest Rate
2. Debt_to_GDP Ratio

## Exploratory Data Analytics (EDA)
The project follows a rigorous EDA process:
1. Data Cleaning: Convert string to numeric floats and mapping month names to datetime objects.
2. Trend Analysis: Visualizing long-term debt accumulation.

## Author
Mathew Kidunda
