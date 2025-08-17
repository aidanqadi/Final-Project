# Final-Project
# Online Retail EDA & Customer Insights

## Overview
This project analyzes the UCI **Online Retail** dataset to surface actionable insights for an e-commerce retailer. The work progresses from idea selection and initial exploration to cleaning and final analysis that answers five business questions (top-revenue products, monthly/seasonal trends, RFM customer segments, top non-UK countries, and the unit price–quantity relationship).

## Purpose
Provide clear, client-ready guidance for **inventory & promotions**, **staffing around seasonal peaks**, **segment-based marketing (RFM)**, **international focus**, and **pricing/bundling tests** using Python (pandas, numpy, matplotlib) in Jupyter.

## Repository Contents
- **Milestone 1** *(Text Document)* — Project idea & client framing; five candidate questions; dataset link/context.
- **Milestone2A** *(Jupyter Notebook)* — Data import and **initial EDA**: `describe()`, `info()`, `shape`, `dtypes`, `head/tail/sample`, column review.
- **Milestone 3** *(Jupyter Notebook)* — **Data cleaning**: remove cancellations (InvoiceNo starting with “C”), keep positive `Quantity`/`UnitPrice`, compute **Revenue = Quantity × UnitPrice**, date/type coercions, notes on NaNs/outliers.
- **Milestone 4** *(Jupyter Notebook)* — **Final analysis & visuals** answering the 5 questions:  
  1) Top products by revenue (Top-10 SKUs)  
  2) Monthly/seasonal sales trend  
  3) RFM segmentation (High-Value / At-Risk / Occasional)  
  4) Top international countries (excluding UK)  
  5) Unit price vs. quantity (correlation/elasticity)  
  Includes concise captions and client-facing conclusions/recommendations.
