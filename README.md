# GitHub API to ADLS Pipeline using Azure Data Factory

  Overview

This project demonstrates a data ingestion pipeline built using Azure Data Factory to extract data from a REST API (GitHub API) and store it in Azure Data Lake Storage Gen2 in CSV format using Copy Data Activity.

  Architecture

GitHub REST API → Azure Data Factory → ADLS Gen2 (CSV)

  Technologies Used

* Azure Data Factory
* REST API (GitHub API)
* HTTP Linked Service
* Azure Data Lake Storage Gen2
* CSV format

  Features

* Extract data from REST API using HTTP linked service
* Use Copy Data Activity for data ingestion
* Convert JSON response to CSV format
* Store processed data in ADLS Gen2
* Batch data processing

  Files in Repository

* fact_sales_data.csv → Sample dataset
* fact_sales_data_2.csv → Processed output data

  Future Improvements

* Add scheduling trigger for automation
* Implement incremental data loading
* Convert CSV to Parquet for better performance
* Integrate with Power BI for visualization

