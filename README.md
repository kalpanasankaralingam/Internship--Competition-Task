# Internship--Competition-Task-1# Property Analysis - BI Developer/Data Analyst Competition Sprint

## 📌 Introduction
The **Property Analysis Competition Sprint** follows industry best practices in **Business Intelligence (BI) and Data Analysis**. This project focuses on designing a **Data Warehouse, implementing an ELT/ETL data pipeline, and modeling data using the Star Schema with a factless fact table**. The goal is to provide a structured approach to **data integration, transformation, and analysis** for property-related insights.

## 📂 Project Overview
### Key Components:
- **Data Engineering**: Design and develop a **Data Warehouse** for property analysis.
- **ETL/ELT Pipeline**: Implement data extraction, transformation, and loading using **SSIS**.
- **Dimensional Modeling**: Create a **Star Schema** with a **factless fact table** for analytical insights.
- **Category Transformation**: Categorize property values into defined price ranges.
- **Visualization**: Power BI dashboards for interactive data exploration.

## 🛠️ Technologies Used
- **SQL Server** (SSMS / SSIS for data import and transformation)
- **SSIS Packages** for automated **data extraction, transformation, and loading**
- **Star Schema with a Factless Fact Table** for data modeling
- **Power BI** for reporting and visualization

## 📑 Project Workflow
### 🔹 Step 1: Data Preparation & Import
- Three datasets were used:
  - `AUS_SubCityDistrictState_Data`
  - `NSW_PropertyMedianValue`
  - `NSW-Public-Schools-Master-Dataset`
- Data was loaded into the **Data Warehouse** using SSIS.
- Load tables were prefixed with `load_` for clarity and organization.

### 🔹 Step 2: Data Modeling
- **Star Schema** was designed following **Kimball's dimensional modeling methodology**.
- A **factless fact table** was included to store event-based data.
- The **Bus Matrix** was used to define the required dimensions and facts.

### 🔹 Step 3: ETL/ELT Implementation
- An **SSIS package** was developed to extract data from load tables.
- Data was transformed and loaded into the **Star Schema Model**.
- **Property value categories** were created using transformation logic:
  - **0-750K**
  - **750K-1.5M**
  - **1.5M-2.5M**
  - **2.5M+**

### 🔹 Step 4: Data Visualization
- Power BI was used to create interactive **dashboards and reports**.
- Data was visualized using **charts, slicers, and geographic maps**.

## 📸 Screenshots
This repository includes:
- **SSIS Package Screenshot**
- **Star Schema Data Model**
- **Bus Matrix**
- **Power BI Visualizations**

## 📝 SQL & SSIS Best Practices Followed
- Standardized **naming conventions** for tables and columns.
- Applied **ETL best practices** to optimize data transformation.
- Used **factless fact tables** to model event-based relationships.
- Ensured **data integrity and indexing** for efficient querying.

## 🏆 Acknowledgments
This project was completed as part of the **BI Developer/Data Analyst Competition Sprint**, focusing on real-world BI solutions and best practices.

---

🔗 **GitHub Repository Link**: [https://github.com/kalpanasankaralingam/Internship--Competition-Task-1]

