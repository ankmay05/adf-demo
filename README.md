# 🚀 Azure Data Pipeline: Azure SQL to ADLS (Bronze Layer)

## 📌 Overview  
This project showcases an **Azure Data Factory (ADF)** pipeline that extracts data from **Azure SQL Database** and loads it into **Azure Data Lake Storage (ADLS Gen2)** using a structured **Bronze-Silver-Gold** architecture.  

---

## 🔧 Technologies Used  
- **Azure Data Factory (ADF)** – Orchestrates the data movement  
- **Azure SQL Database** – Source database storing raw data  
- **Azure Data Lake Storage (ADLS Gen2)** – Stores data in a layered structure  
- **GitHub Integration** – Version control for managing ADF changes  

---

## 📂 ADLS Folder Structure  
- **Bronze Layer** – Stores raw data ingested from Azure SQL  
- **Silver Layer** – (Upcoming) Processed and cleaned data  
- **Gold Layer** – (Upcoming) Business-ready analytics data  

---

## 🔄 Data Pipeline Workflow  
1. Set up an **Azure SQL Database** and upload sample data.  
2. Configure **Azure Data Lake Storage (ADLS Gen2)** with the Bronze-Silver-Gold folder structure.  
3. Create **Linked Services** in ADF for Azure SQL and ADLS.  
4. Define **Datasets** for both the source (SQL) and destination (ADLS).  
5. Develop a **Copy Data Pipeline** to transfer data from SQL to the Bronze folder in ADLS.  
6. **Publish & Trigger** the pipeline to validate the data movement.  
7. Utilize **GitHub integration** for version control to track pipeline changes.  

---

## 🚀 Next Steps  
- Implement **Data Flow** to transform and load data into the Silver layer.  
- Optimize the pipeline for **incremental data loading**.  
- Automate the pipeline using **triggers** for scheduled or real-time execution.  

---

## 🤝 Contribution  
If you find this project helpful, feel free to **fork**, suggest improvements, or contribute by adding transformations for the Silver layer!  
