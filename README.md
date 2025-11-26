# Retail_Sales_Database
This repository contains the analysis and insights derived from the "Sales Case Study.csv" dataset, which simulates the daily trading information for a single retail product.
#Objective
The primary objective of this case study is to develop key metrics and derive subsequent business insights from the provided sales data. This analysis aims to understand product performance, pricing strategy impact, and profitability.

Dataset DescriptionThe Sales Case Study.csv file provides daily aggregated data with the following fields:FieldDescriptionDateThe specific day the sales occurred.SalesTotal monetary (Rand) value of sales for the day.Cost of SalesTotal monetary (Rand) value of the cost of goods sold for the day.Quantity SoldTotal number of units sold for the day.

Metrics to be DevelopedThe core analysis focuses on calculating the following metrics:Daily Sales Price Per Unit: The average price at which a single unit was sold each day.Calculation: $\text{Sales} / \text{Quantity Sold}$Average Unit Sales Price: The overall average price of the product across the entire dataset period.Daily % Gross Profit: The daily gross profit margin as a percentage of Sales.Calculation: $((\text{Sales} - \text{Cost of Sales}) / \text{Sales}) \times 100$Daily % Gross Profit Per Unit: The daily gross profit margin derived from a single unit's sale.Calculation: $((\text{Sales} - \text{Cost of Sales}) / \text{Quantity Sold}) / (\text{Sales} / \text{Quantity Sold}) \times 100$(Note: This simplifies to the Daily % Gross Profit).

Key Insights to be Derived
A significant part of the analysis involves investigating the impact of price changes:

Promotional Analysis (Price Elasticity of Demand - PED):

Identify three distinct periods where the product was likely on promotion/special (indicated by a noticeable drop in unit price).

Calculate the Price Elasticity of Demand (PED) for each of these three periods to measure how sensitive the quantity sold is to price changes.

Provide an opinion on whether the product performs better or worse when sold at a promotional price, based on the PED and associated sales/profit data.

Additional Insights:

Derive and present any other interesting KPIs, metrics, visuals, or reports discovered during the exploration of the dataset.
Analysis Structure
The analysis will be structured to:

Data Preparation: Load, clean, and validate the dataset.

Metric Calculation: Compute the daily and aggregated metrics.

Promotional Deep Dive: Identify promotion periods and calculate PED.

Conclusion & Reporting: Present additional insights, visuals, and final conclusions.



