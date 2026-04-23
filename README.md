# Transit Payment Analytics Dashboard

## Overview
This project is a Power BI dashboard built to analyze transit payment and ridership trends using curated TTC monthly KPI data compiled from public reports. The dashboard focuses on fare revenue, revenue rides, and changes in payment-method adoption over time.

## Objective
The goal of this project was to build an interactive dashboard that tracks key performance indicators and clearly communicates payment and usage trends to non-technical stakeholders.

## Tools Used
- Power BI
- Excel / CSV
- Public TTC KPI reports

## Dataset
The dataset was manually compiled from TTC public KPI reports and structured into two CSV files:

- `ttc_payment_kpi_final.csv`  
  Summary table containing period-level metrics such as fare revenue, revenue rides, and payment-method shares.

- `ttc_payment_mix_final.csv`  
  Long-format table used for payment mix visualizations by period and payment type.

## Key Metrics
- Total Fare Revenue
- Total Revenue Rides
- Fare Revenue per Ride
- Open Payment Share
- Virtual PRESTO Share
- Physical PRESTO Share
- Cash Share
- Legacy Fare Share

## Dashboard Features
- KPI cards for high-level performance tracking
- Line charts showing fare revenue and revenue rides by period
- Stacked column chart showing payment mix over time
- Bar chart showing the latest payment mix snapshot
- Insight section summarizing major trends

## Key Insights
- Open Payment and Virtual PRESTO increased steadily across the reporting periods.
- Physical PRESTO remained the dominant payment method, but its share declined over time.
- Fare revenue and revenue rides fluctuated by period, with notable peaks in 2024 P9, 2024 P12, and 2025 P3.

## Data Source
This project uses curated TTC monthly KPI data compiled from public TTC reports, including reporting periods from 2024 P7 to 2025 P5.

## Files
- `ttc_payment_kpi_final.csv`
- `ttc_payment_mix_final.csv`
- `dashboard_screenshot.png`

## Dashboard Preview
![Dashboard Preview](Transit%20Payment%20Analytics%20Dashboard-1.png)
