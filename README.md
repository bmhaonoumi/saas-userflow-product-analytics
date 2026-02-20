# SaaS - UserFlow Product Analytics

## Objective
Identify at-risk subscribers and optimize feature investment using behavioral, billing, and support data.

## Architecture
Medallion Architecture:
- Bronze: Raw ingestion (JSON, CSV)
- Silver: Engagement normalization, CDC, sentiment analysis
- Gold: Churn risk scoring and feature ROI analysis

## Key Outputs
- customer_churn_risk table
- feature_roi_table
- Masked analytical views

## Technologies Used
- Databricks (Serverless)
- Delta Lake
- SQL
- Medallion Architecture
