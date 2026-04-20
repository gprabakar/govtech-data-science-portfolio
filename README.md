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
