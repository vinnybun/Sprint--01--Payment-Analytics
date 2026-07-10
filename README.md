# Sprint--01--Payment-Analytics
This is my first task as a fintech data scientist 

## Project Overview
Transaction Data Profiling for Payment Analysis

## Business Problem
A fintech company processes millions of transactions daily. Before developing dashboards or fraud detection models, the analytics team needs to understand the quality, structure and potential of the transaction data.

This project profiles the dataset and idntifies opportunites for futuree analytics and machine learning woerk.

## Dataset
The **PaySim Mobile Money Transaction Dataset** was used for this analytics task. It is a synthethic task that is based on real-world transaction patterns and hences serves the purpose of providing a true representation of the real world use case since there are not enough publicly available financial data.

## Objectives
- Understand the dataset.
- Assess data quality.
- Identify potential business use cases.
- Prepare for exploratory analysis.
- Lay the groundwork for fraud detection.

## Technologies Used
- Python
- Pandas
- Jupyter Notebook

## Key Findings
- Fraud labels are available, making this dataset useful for supervised learning problems.
- Some transactions that were fraudulent were not flagged as fraudulent.
- There is a pattern to how fraud transactions are carried out.
- All fraudulent transactions first transfer the amount out, and this doesn't get captured in the destination account.
- After the fraudulent transfer, a cashout is made.
