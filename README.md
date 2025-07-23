# Matern Care Analytics 
**Project Overview**:  
This project aims to provide comprehensive analytics on the Pregnancy Risk Assessment Monitoring System (PRAMS) data from 2011, which is archived by the Centers for Disease Control and Prevention (CDC). The dataset comprises 520,000 survey responses and serves as a crucial resource for understanding maternal and child health in the United States. The project leverages advanced data processing and analytics techniques to extract valuable insights from this extensive dataset.

### Data Ingestion:
1. **Input File**: The data is provided in a CSV format, which is a common structure for survey data.
2. **Storage**: The CSV file is ingested into Azure Data Lake Storage, specifically within a Bronze container. The Bronze container typically serves as the raw data storage layer, where data is kept in its original format.

### Data Processing:
3. **Transformation**: The data is loaded and transformed into Delta Silver tables. In this step, data cleaning and preprocessing occur, which may include handling missing values, correcting data types, and other transformations to prepare the data for analysis.
4. **Data Modeling**: Post transformation, the Silver tables are restructured into a star schema in Gold Delta tables.

Anlytics Platform and Technologies: Databricks notebooks, PySpark, SQL, Azure, ADF, Delta Live tables, DataLake house, workflows and orchetrations

5.  **Reporting and Anlytics**
<img width="1156" height="689" alt="Screenshot 2025-07-22 at 10 39 04 PM" src="https://github.com/user-attachments/assets/84c6cb56-b286-409f-afc2-7ad07233fc29" />
