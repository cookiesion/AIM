# AIM
AI-ML Capstone Project
Retail Sales Insights Using Unsupervised Learning

## Overview
This project analyzes transaction-level retail sales data from an early-stage business to extract product-level insights using unsupervised learning techniques.

## Business Context
- No customer-level data available
- Business started operations in October 2025
- Focus on short-term sales patterns and product performance

## Dataset
Features include:
- Date and time of purchase
- Item purchased and item type
- Unit price, quantity, total purchase value

## Methods
- Exploratory Data Analysis (EDA)
- Feature engineering at the product level
- KMeans clustering
- Cluster evaluation using Silhouette Score

## Repository Structure
src/ # Python scripts
notebooks/ # Jupyter/Colab notebooks
data/ # Raw and processed data
models/ # Saved models
reports/ # Final report


## How to Reproduce
1. Install dependencies: `pip install -r requirements.txt`
2. Run notebooks in order under `notebooks/`
3. Execute scripts in `src/` to regenerate models

## Outputs
- Product clusters
- Business insights for inventory planning

