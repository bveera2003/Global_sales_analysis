# Global_sales_analysis

Project Overview:
This project focuses on designing and implementing a cloud-based ETL (Extract, Transform, Load) pipeline to consolidate, clean, and analyze global sales data from 8 different countries using Google Cloud Platform (GCP). The final goal is to provide business insights through visual dashboards using BigQuery and Looker Studio.

  Objectives:
	-Collect sales data from various formats and sources across 8 countries.
	-Clean and normalize all datasets into a unified structure using Apache Beam in Dataflow.
	-Convert all sales amounts into INR using fixed conversion rates.
	-Merge and store the cleaned dataset in Google BigQuery.
	-Build interactive dashboards to analyze global sales performance.

    
  Tech Stack:
	-Google Cloud Storage: Store raw and intermediate files
	-Dataflow (Apache Beam): Data cleaning, conversion, and merging
	-BigQuery: Final storage and analysis
	-Looker Studio: Visual dashboards
	-SQL Server / MySQL / AlloyDB: Country-specific data sources

  Key Insights Enabled:
	-Total sales and average order value per country
	-Most profitable product categories globally
	-Region-wise sales breakdown
	-Comparison of online vs offline sales
	-Monthly sales trends across continents

  Future Enhancements:
	-Integrate real-time ingestion using Cloud Pub/Sub
	-Use Cloud Composer for orchestration
	-Implement machine learning for sales forecasting
