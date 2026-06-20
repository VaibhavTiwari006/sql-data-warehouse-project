# SQL Data Warehouse Project

<a href="https://www.linkedin.com/in/vaibhavtiwari006/">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin"/>
</a>

<br><br>

Built an end-to-end SQL Data Warehouse using SQL Server using a layered architecture approach (Bronze → Silver → Gold), implementing ETL pipelines, data transformation, data quality validation, and analytical modeling.

---

## Project Overview

This project demonstrates the design and implementation of a modern SQL Data Warehouse architecture.

The pipeline extracts data from multiple source systems, transforms and standardizes records, validates data quality, and loads curated analytical datasets for reporting and business analysis.

### Objectives

* Build a scalable warehouse architecture
* Implement ETL workflows using SQL
* Perform data cleansing and transformation
* Apply data quality validation
* Create analytical datasets for reporting and analytics

---

## Architecture

### Data Warehouse Architecture

![Data Warehouse Architecture](docs/architecture/Data_Warehouse.png)

---

### Data Integration

![Data Integration](docs/integration/Data_Integration.png)

---

### Data Flow Diagram

![Data Flow Diagram](docs/flow/Data_Flow.png)

---

## Project Structure

```plaintext
sql-data-warehouse-project/
│
├── datasets/
│   ├── crm/
│   └── erp/
│
├── docs/
│   ├── architecture/
│   ├── integration/
│   └── flow/
│
├── scripts/
│   ├── bronze/
│   ├── silver/
│   └── gold/
│
├── tests/
│
├── README.md
└── LICENSE
```

---

## Data Pipeline

### Bronze Layer

Stores raw data extracted from source systems with minimal transformation.

### Silver Layer

Performs cleansing, standardization, enrichment, and data quality improvement.

### Gold Layer

Creates business-ready analytical datasets for reporting and decision-making.

---

## Data Sources

### CRM Data

Contains customer and transactional data.

### ERP Data

Contains operational and business process data.

---

## Data Quality Validation

Quality checks implemented for:

* Null value detection
* Duplicate record checks
* Data consistency validation
* Business rule validation

---

## Technologies Used

* SQL Server
* SQL Server Management Studio (SSMS)
* T-SQL
* Draw.io
* Git
* GitHub
* Notion

---

## How to Run

1. Initialize the database
2. Execute Bronze layer scripts
3. Execute Silver layer scripts
4. Execute Gold layer scripts
5. Execute data quality checks

---

## Outcomes

* Implemented a layered warehouse architecture
* Built ETL workflows using SQL
* Automated data transformation processes
* Applied data quality validation
* Generated analytical datasets

---

## License

This project is licensed under the MIT License.
