# Case Prioritization Machine Learning System

## Project Overview
This project builds a Machine Learning classification system to prioritize citizen cases based on severity and socio-economic risk indicators.

The objective is to help social workers and public agencies identify high-priority cases requiring urgent attention.

## Problem Statement
Classify cases into priority levels:
- High priority
- Medium priority
- Low priority

based on case severity, health condition, financial situation, and family dependents.

## Dataset
Synthetic dataset representing case management information.

Features:
- severity_score
- income_level
- health_flag
- dependents
- previous_cases

Target:
- priority_level

## Machine Learning Approach
- Label Encoding for categorical output
- Gradient Boosting Classification model
- Model evaluation using classification metrics
- Priority distribution visualization

## Key Results
The model successfully classifies cases into priority categories based on risk indicators.

Helps decision makers:
- Identify urgent cases quickly
- Allocate resources efficiently
- Improve response time

## Business Impact
Supports government case management systems by:
- Improving prioritization accuracy
- Enabling proactive interventions
- Enhancing service delivery efficiency

## Technologies Used
- Python
- pandas
- numpy
- scikit-learn
- matplotlib

## How to Run
1. Run notebook cells sequentially
2. Dataset will be generated automatically
3. Model will classify case priority

## Future Improvements
- Deploy dashboard for case monitoring
- Integrate real-world case management datasets
- Apply explainable AI techniques
# Citizen Service Optimization Model

## Project Overview
This project develops a Machine Learning model to optimize public service efficiency by predicting waiting times based on operational conditions.

Government agencies aim to improve citizen experience by reducing waiting time and optimizing resource allocation.

## Problem Statement
Predict waiting time in public service centers using operational features such as queue length, staff availability, and service demand patterns.

## Dataset
Synthetic dataset simulating public service center operations.

Features:
- queue_length
- staff_available
- service_type
- hour_of_day
- day_of_week

Target:
- waiting_time

## Machine Learning Approach
- Linear Regression model
- Feature relationship analysis
- Prediction accuracy evaluation
- Visualization of actual vs predicted waiting times

## Key Results
Model predicts service waiting time based on operational variables, enabling optimization recommendations.

Insights include:
- High queue length increases waiting time
- Increased staff availability reduces waiting time
- Peak service hours influence service efficiency

## Business Impact
Supports Smart Nation initiatives by:
- Improving citizen experience
- Reducing service delays
- Optimizing workforce allocation

## Technologies Used
- Python
- pandas
- numpy
- scikit-learn
- matplotlib

## How to Run
1. Run notebook cells sequentially
2. Synthetic dataset will be generated automatically
3. Model will predict waiting time

## Future Improvements
- Use real operational datasets
- Apply advanced regression models
- Build real-time dashboard for monitoring service efficiency
# Public Policy Data Analysis

## Project Overview
This project analyzes public policy trends using statistical and data visualization techniques. The goal is to understand relationships between government spending and socio-economic outcomes.

Public sector organizations rely on data-driven insights to evaluate policy effectiveness and improve long-term planning.

## Problem Statement
Analyze how public spending influences socio-economic indicators such as employment rate and life expectancy.

## Dataset
Synthetic time-series dataset representing yearly policy indicators.

Features:
- year
- education_spending
- health_spending
- employment_rate
- life_expectancy

## Analytical Approach
- Time series trend visualization
- Correlation analysis
- Statistical interpretation of policy impact
- Data visualization using heatmaps and line charts

## Key Insights
Analysis helps identify relationships between:
- Education spending and employment outcomes
- Healthcare investment and life expectancy
- Long-term policy effectiveness

## Business Impact
Supports evidence-based policymaking by:
- Providing data insights for government decision makers
- Identifying trends and patterns in socio-economic indicators
- Improving public policy effectiveness

## Technologies Used
- Python
- pandas
- numpy
- matplotlib
- seaborn

## How to Run
1. Open Jupyter Notebook
2. Execute cells sequentially
3. Charts and correlation matrix will be generated

## Future Improvements
- Use real-world datasets from World Bank or government portals
- Add predictive forecasting models
- Create interactive dashboards
# Social Risk Prediction Model

## Project Overview
This project develops a Machine Learning model to identify individuals or households at risk of requiring social support. The goal is to enable early intervention and proactive decision-making aligned with Smart Nation initiatives.

Government agencies often need to identify vulnerable populations early to provide timely assistance such as financial aid, healthcare support, or employment services.

## Problem Statement
Predict whether a citizen is at high social risk based on socio-economic indicators such as income, employment status, household size, education level, and medical conditions.

## Dataset
Synthetic dataset simulating real-world socio-economic indicators:

Features:
- age
- income
- employment_status
- household_size
- education_level
- medical_condition
- previous_assistance

Target:
- high_risk (0 = low risk, 1 = high risk)

## Machine Learning Approach
- Data preprocessing using pandas
- Feature engineering
- Random Forest Classification model
- Model evaluation using classification metrics

## Key Results
The model successfully predicts individuals with higher probability of needing early social support.

Feature importance analysis identifies major risk drivers such as:
- Low income
- Unemployment
- Medical conditions
- Previous financial assistance

## Business Impact
Supports proactive government intervention strategies by:
- Identifying vulnerable populations early
- Enabling targeted resource allocation
- Improving social welfare outcomes

## Technologies Used
- Python
- pandas
- numpy
- scikit-learn
- matplotlib

## How to Run
1. Open Jupyter Notebook
2. Run notebook cells sequentially
3. Dataset will be generated automatically
4. Model training and evaluation results will be displayed

## Future Improvements
- Deploy dashboard using Streamlit
- Integrate real-world socio-economic datasets
- Improve model performance using XGBoost
