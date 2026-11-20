<h1 align="center">Surekha</h1>
<h3 align="center">Data Engineer | Data Scientist | Data Analyst | Software Engineer</h3>
<p align="center">Azure Data Factory · Azure Databricks · Delta Lake · Unity Catalog · ADLS Gen2 · SQL · Python · PySpark</p>

<p align="center">
  <a href="https://github.com/surekhag28"><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" alt="GitHub"/></a>
</p>

---

## About Me

I am a data professional based in Australia, focused on building reliable, scalable data pipelines on Microsoft Azure.

My experience spans the full data lifecycle:

| Role | Focus |
|---|---|
| **Software Engineer** | Building and maintaining applications, writing clean, tested code and working with version control |
| **Data Analyst** | Turning business data into reports and insights using SQL, Python and dashboards |
| **Data Scientist** | Exploring data, building statistical and machine learning models, and communicating findings |
| **Data Engineer** | Designing ingestion pipelines, data models and audit frameworks on Azure |

Along the way, I have worked with retail sales data for community stores at Monash University and with complaints and audit data at ResMed. I now bring this combined software, analytics and data science background to cloud data engineering, building end-to-end data platforms with Azure Data Factory, Azure Databricks and Delta Lake.

- Building metadata-driven ingestion pipelines with full, append and merge (incremental) loads
- Designing medallion architectures (bronze, silver, gold) in Azure Databricks with Unity Catalog governance
- Designing audit logging, watermark management, failure handling and email alerting for production-style pipelines
- Turning gold-layer data into business dashboards with Databricks AI/BI

---

## Technical Skills

| Area | Tools and Technologies |
|---|---|
| **Languages** | ![SQL](https://img.shields.io/badge/SQL-336791?style=flat&logo=postgresql&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white) |
| **Data Integration & Orchestration** | ![Azure Data Factory](https://img.shields.io/badge/Azure%20Data%20Factory-0078D4?style=flat&logo=microsoftazure&logoColor=white) ![Azure Logic Apps](https://img.shields.io/badge/Azure%20Logic%20Apps-0078D4?style=flat&logo=microsoftazure&logoColor=white) |
| **Data Processing** | ![Databricks](https://img.shields.io/badge/Azure%20Databricks-FF3621?style=flat&logo=databricks&logoColor=white) ![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat&logo=apachespark&logoColor=white) ![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD4?style=flat&logo=delta&logoColor=white) |
| **Storage and Databases** | ![ADLS Gen2](https://img.shields.io/badge/ADLS%20Gen2-0078D4?style=flat&logo=microsoftazure&logoColor=white) ![Azure SQL Database](https://img.shields.io/badge/Azure%20SQL%20Database-0078D4?style=flat&logo=microsoftsqlserver&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) |
| **Governance and Security** | ![Unity Catalog](https://img.shields.io/badge/Unity%20Catalog-FF3621?style=flat&logo=databricks&logoColor=white) ![Azure Key Vault](https://img.shields.io/badge/Azure%20Key%20Vault-0078D4?style=flat&logo=microsoftazure&logoColor=white) ![Managed Identity](https://img.shields.io/badge/Managed%20Identity-0078D4?style=flat&logo=microsoftazure&logoColor=white) |
| **Analytics** | ![Databricks AI/BI](https://img.shields.io/badge/Databricks%20AI%2FBI%20Dashboards-FF3621?style=flat&logo=databricks&logoColor=white) ![Databricks Genie](https://img.shields.io/badge/Databricks%20Genie-FF3621?style=flat&logo=databricks&logoColor=white) |
| **Version Control** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white) |
| **Currently Learning** | ![Microsoft Fabric](https://img.shields.io/badge/Microsoft%20Fabric-117865?style=flat&logo=microsoft&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat&logo=terraform&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white) |

---

## Featured Project

### ⭐ [CareSync – End-to-End Healthcare Data Platform on Azure](https://github.com/surekhag28/caresync-data-platform)

A metadata-driven data platform for a network of 50 hospitals. It ingests data from **PostgreSQL** and partner **CSV** files with **Azure Data Factory**, processes it through a **bronze → silver → gold** medallion architecture in **Azure Databricks** under **Unity Catalog**, and powers a **4-page Databricks AI/BI dashboard** on patient risk, hospital performance and lab test trends.

<p align="center">
  <a href="https://github.com/surekhag28/caresync-data-platform">
    <img src="https://raw.githubusercontent.com/surekhag28/caresync-data-platform/main/docs/caresync_architecture.png" width="750" alt="CareSync architecture">
  </a>
</p>

| Area | Highlights |
|---|---|
| **Ingestion** | Metadata-driven ADF pipelines driven by a control database (config, watermark and audit tables); FULL, APPEND and MERGE loads |
| **Processing** | PySpark and Spark SQL notebooks, Delta Lake `MERGE`, three gold tables built from a source-to-target mapping (STTM) |
| **Governance** | Unity Catalog with storage credential, external locations, volumes and managed tables; secrets in Key Vault |
| **Operations** | Audit logging per table and run, failure handling, and HTML email alerts through Azure Logic Apps |
| **Analytics** | 4-page AI/BI dashboard: Executive Overview, Hospital Performance, Lab Test Insights, Patient Population and Risk |

📘 [Project overview](https://github.com/surekhag28/caresync-data-platform) · ⚙️ [ADF pipelines](https://github.com/surekhag28/adf-data-engineering-caresync) · 🧱 [Databricks notebooks](https://github.com/surekhag28/adb-caresync)

---

## More Projects

### [Azure Data Platform Projects](https://github.com/surekhag28/azure-data-platform-projects)

A series of hands-on Azure Data Factory projects, progressing from basic file copies to a complete metadata-driven ingestion framework.

| # | Project | Highlights |
|---|---|---|
| 01 | [Basic File Copy](https://github.com/surekhag28/azure-data-platform-projects/blob/main/docs/01-basic-copy-single-file/README.md) | Linked services, datasets, Copy activity, parameters, managed identity |
| 02 | [Multiple File Copy](https://github.com/surekhag28/azure-data-platform-projects/blob/main/docs/02-basic-copy-multiple-files/README.md) | Get Metadata, ForEach, dynamic file naming |
| 03 | [Copy SQL Tables to ADLS Gen2](https://github.com/surekhag28/azure-data-platform-projects/blob/main/docs/03-basic-copy-sql-tables/README.md) | Lookup, configuration table, parameterised datasets |
| 04 | [Metadata-Driven Full and Incremental Ingestion](https://github.com/surekhag28/azure-data-platform-projects/blob/main/docs/04-complete-data-ingestion/README.md) | Parent and child pipelines, watermark-based incremental loads, stored procedures, success and failure audit logging |

---

## Current Focus

- Adding CI/CD for Azure Data Factory and Databricks with GitHub Actions and Databricks Asset Bundles
- Infrastructure as code with Terraform
- Data quality checks, streaming ingestion with Auto Loader and Event Hubs
- Building the same pipelines in Microsoft Fabric
