# MaternCare Anlytics 
These measures are intended to drive improvements in maternal health. By providing care to pregnant women that follows best practices that advance health care quality, safety, and equity, hospitals and doctors can improve chances for a safe delivery and a healthy baby.These measures are intended to drive improvements in maternal health. By providing care to pregnant women that follows best practices that advance health care quality, safety, and equity, hospitals and doctors can improve chances for a safe delivery and a healthy baby.

This projet also provides anlytics on PRAMS (the Pregnancy Risk Assessment Monitoring System) 2011 archived dats by CDC, with 520K survey responses.
Input ingested file in CSV format. File is ingested to a Azure datalake storage in Bronze container. Loaded and transformed to delta Silver tables and then tables redesigned with star schema in gold delta tables to generate reports and anlytics. 

Anlytics Platform and Technologies: Databricks notebooks, PySpark, SQL, Azure, ADF, Delta Live tables, DataLake house, workflows and orchetrations

Output: Anlytics
<img width="1156" height="689" alt="Screenshot 2025-07-22 at 10 39 04 PM" src="https://github.com/user-attachments/assets/84c6cb56-b286-409f-afc2-7ad07233fc29" />
