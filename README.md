<div align="center">

# 🚀 SQL Data Warehouse & Analytics Project

### Building a Modern Data Warehouse Using SQL Server


## 📌 About The Project

This project demonstrates the development of a modern data warehouse using **Microsoft SQL Server**.

The objective is to consolidate sales data from different source systems (ERP and CRM), perform data cleansing and transformation, and develop a structured data warehouse for analytical reporting.

The project follows the **Medallion Architecture (Bronze, Silver, and Gold)** to organise data systematically and improve its usability for business intelligence and analytics.

## 🎯 Project Objectives

- 🏗️ Design and develop a modern SQL-based data warehouse.
- 🔗 Integrate data from multiple ERP and CRM source systems.
- 🧹 Perform data cleaning, standardisation, and transformation.
- ⚙️ Implement ETL (Extract, Transform, Load) processes.
- 📊 Develop Fact and Dimension tables using Star Schema modelling.
- 🔍 Analyse customer behaviour, product performance, and sales trends.
- 💡 Generate meaningful business insights through SQL queries.

## 📋 Business Requirements

### 1️⃣ Data Engineering – Data Warehouse Development

**Objective:** Develop a centralised data warehouse to consolidate sales data and support analytical reporting.

| Requirement | Description |
|---|---|
| Data Sources | ERP and CRM datasets provided in CSV format |
| Data Quality | Identify and resolve missing values, duplicates, and inconsistencies |
| Data Integration | Combine multiple source systems into a unified data model |
| Data Architecture | Implement Bronze, Silver, and Gold layers |
| Data Modelling | Develop Fact and Dimension tables |
| Documentation | Document data architecture and data models |

### 2️⃣ Data Analysis – Analytics & Reporting

**Objective:** Develop SQL-based analytical queries to generate actionable business insights.

Key analytical areas:

- 👥 Customer Behaviour Analysis
- 📦 Product Performance Analysis
- 📈 Sales Trend Analysis

---

## 🏛️ Data Architecture – Medallion Architecture

The project follows the Medallion Architecture, consisting of three layers:

| Layer | Description |
|---|---|
| 🥉 Bronze | Stores raw data directly from ERP and CRM CSV files. |
| 🥈 Silver | Performs data cleansing, standardisation, and transformation. |
| 🥇 Gold | Stores business-ready data structured using a Star Schema. |

### Data Flow

```text
       ERP DATA             CRM DATA
           |                   |
           v                   v
        CSV FILES           CSV FILES
           |                   |
           +---------+---------+
                     |
                     v
             🥉 BRONZE LAYER
                Raw Data
                     |
                     v
             🥈 SILVER LAYER
          Cleaned & Standardised
                     |
                     v
              🥇 GOLD LAYER
               Star Schema
                     |
                     v
           ANALYTICS & REPORTING
                     |
                     v
          Business Intelligence
```

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Microsoft SQL Server | Database and data warehouse development |
| SQL | Data extraction, transformation, and analysis |
| SQL Server Management Studio | Database management and query execution |
| Draw.io | Data architecture and modelling diagrams |
| GitHub | Version control and project documentation |
| Notion | Project planning and task management |

## 📂 Repository Structure

```text
sql-data-warehouse-project/
│
├── datasets/
│   ├── source_erp/
│   ├── source_crm/
│   └── placeholder/
│
├── docs/
│   ├── data_architecture.png
│   └── data_model.png
│
├── scripts/
│   ├── bronze/
│   ├── silver/
│   ├── gold/
│   └── init_database.sql
│
├── README.md
└── LICENSE
```

## 📊 Expected Deliverables

- ✅ SQL Server Data Warehouse
- ✅ ERP and CRM Data Integration
- ✅ ETL SQL Scripts
- ✅ Bronze, Silver, and Gold Data Layers
- ✅ Fact and Dimension Tables
- ✅ Star Schema Data Model
- ✅ Customer, Product, and Sales Analysis
- ✅ Project Documentation

## ⚙️ Getting Started

### Prerequisites

Make sure you have the following installed:

1. [Microsoft SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
2. [SQL Server Management Studio (SSMS)](https://learn.microsoft.com/en-us/ssms/install/install)
3. [Git](https://git-scm.com/)

### Installation

```bash
# Clone the repository
git clone https://github.com/YOUR-USERNAME/sql-data-warehouse-project.git

# Navigate to the project directory
cd sql-data-warehouse-project
```

Next:

1. Import the ERP and CRM datasets.
2. Set up the SQL Server database.
3. Execute the database initialisation scripts.
4. Develop the Bronze, Silver, and Gold layers.
5. Execute SQL queries for analytical reporting.

---

## 👨‍💻 About Me

**Swarnava Biswas**

🎓 PGDM (Finance) – International Management Institute, Bhubaneswar

📚 B.Com (Hons.) – Accounting and Finance

I am interested in financial analysis, data analytics, SQL development, and business intelligence.

Currently developing my technical skills in SQL, Python, Power BI, and data analytics to combine financial knowledge with data-driven decision-making.

### Connect With Me

- 💼 LinkedIn: [My LinkedIn Profile](https://www.linkedin.com/)
- 🐙 GitHub: [My GitHub Profile](https://github.com/)

---

## 📜 License

This project is licensed under the **MIT License**.

You are free to use, modify, distribute, and adapt this project, subject to the conditions of the MIT License.

See the [LICENSE](LICENSE) file for details.

---

<div align="center">

### ⭐ If you find this project useful, consider giving it a star!

**Built with ❤️ using SQL Server**

</div>
