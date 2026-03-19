# RFM Customer Segmentation Analysis 

## Overview

This project focuses heavily on customer segmentation using RFM (Recency, Frequency, Monetary) analysis. The primary objective is to transform raw, transactional data into actionable marketing insights by categorizing customers based on their purchasing behavior. Instead of relying on manual, offline processing of CSV files, which is inefficient and difficult to reproduce, this project leverages Google BigQuery for cloud-based data storage and processing. This allows for scalable data manipulation and the creation of a centralized data warehouse, ensuring that all transformations are traceable, clean, and ready for business intelligence tools. Following the data engineering phase in the cloud, the project utilizes Power BI to connect directly to the BigQuery database, facilitating the creation of an interactive dashboard. This dashboard is designed to drive strategic marketing decisions by providing a visual representation of customer segments, such as identifying 'Champions' or 'At-Risk' customers. The workflow emphasizes the transition from manual, local data manipulation to a sophisticated, automated approach that utilizes traceable SQL code for ETL (Extract, Transform, Load) logic.

## Tools Used
* Google BigQuery: SQL data processing & storage
* Power BI: Data visualization & dashboarding
