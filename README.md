# Vendor_Risk_Dashboard
Global Vendor Intelligence &amp; Risk Dashboard using Power BI, SQL concepts, and data analytics

## Project Overview

This project focuses on analyzing supplier performance and procurement data to identify high-risk vendors and improve sourcing decisions. The solution integrates multiple datasets and applies analytical techniques to provide actionable insights for procurement teams.

## Objectives

* Evaluate supplier performance based on delivery and quality metrics
* Identify high-risk vendors using a scoring model
* Analyze procurement spend across categories and regions
* Enable data-driven decision-making in vendor management

## Data Sources

* Supply chain dataset containing supplier performance metrics such as delivery delay, defect rate, and location
* Spend analysis dataset containing transaction-level procurement data including order value, category, and supplier information

## Data Preparation

* Cleaned and standardized datasets using Power Query
* Resolved inconsistencies in supplier names through text transformations
* Created a unified data model by merging datasets on supplier attributes
* Generated a surrogate key (Supplier_ID) to establish relationships

## Methodology

* Performed data transformation and integration using Power BI Power Query
* Applied data modeling techniques to structure relationships between datasets
* Developed calculated columns using DAX for risk evaluation

## Risk Scoring Model

A weighted scoring approach was used to evaluate supplier risk:

Risk Score = 0.6 × Delivery Delay + 0.4 × Quality Defect Rate

Suppliers were classified into three categories:

* Low Risk
* Medium Risk
* High Risk

## Dashboard Features

### Executive Summary

* Total spend, total orders, and average risk score
* Spend distribution by supplier and category
* Risk distribution across suppliers
  ![Executive Summary](https://github.com/user-attachments/assets/c0995425-cb38-45b9-9de0-64d91376416a)


### Vendor Risk Matrix

* Scatter plot analysis of supplier cost versus delivery performance
* Identification of high-cost and high-risk vendors
  ![Vendor Risk Matrix](https://github.com/user-attachments/assets/dad6718e-0e6f-494b-8e4e-f40a877c854b)


### Risk Insights

* Average risk score by country
* Identification of high-risk suppliers
* Risk distribution analysis with interactive filterin
  ![AI Insights](https://github.com/user-attachments/assets/84a238c6-3d2b-499f-8fbb-7f5645db4025)


## Key Insights

* Detected suppliers with high delivery delays and defect rates contributing to elevated risk
* Identified spending concentration among a limited set of vendors
* Highlighted opportunities for vendor consolidation and performance improvement

## Business Impact

* Enables proactive identification of supplier risks
* Supports strategic sourcing and vendor rationalization
* Improves procurement efficiency through data-driven insights

## Tools and Technologies

* Power BI (Data Modeling, DAX, Visualization)
* Excel / CSV (Data Sources)
* Data Transformation using Power Query

## Repository Contents

* Power BI dashboard file (.pbix)
* Source datasets (.csv)
* Dashboard screenshots

## Future Enhancements

* Integration with real-time procurement systems
* Incorporation of external data such as currency fluctuations and market trends
* Advanced predictive modeling for supplier risk forecasting
