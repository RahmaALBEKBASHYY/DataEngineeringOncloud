# Data Engineering on Cloud Project

## Project Overview
This project processes and analyzes the European election results in Paris for the years 2014, 2019, and 2024 using Azure Data Lake Storage Gen2, Azure Databricks, and Power BI.

## Contributors
- Rahma ALBEKBASHY
- Doha HAJJOU

## Technologies Used
- Azure Data Lake Storage Gen2
- Azure data warehouse 
- Azure Databricks
- Power BI

## Project Steps

1. **Creating the Data Lake**:
   - Created an Azure Storage Account.
   - Enabled Azure Data Lake Storage Gen2.

2. **Creating Staging and Data Warehouse Containers**:
   - Created `staging` and `datawarehouse` containers.
   - Loaded raw data into the `staging` container.

3. **Loading Raw Data**:
   - Deployed a Databricks cluster.
   - Loaded and processed data in the dataWarehouse.

4. **Data Transformation with Azure Databricks**:
   - Used PySpark to clean, transform, and analyze data.

5. **Power BI Integration and Dashboard Creation**:
   - Connected Power BI to Azure Blob Storage.
   - Created interactive dashboards for visualization.

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/RahmaALBEKBASHYY/dataengineeringoncloud.git
    cd dataengineeringoncloud
    ```

2. Set up Azure services and load raw data into the staging container.

3. Use the provided Databricks notebooks and scripts for data processing and analysis.

## Conclusion
This project showcases the use of Azure cloud services for effective data engineering and visualization.

---

For detailed documentation and code, refer to the provided scripts and notebooks in the repository.
