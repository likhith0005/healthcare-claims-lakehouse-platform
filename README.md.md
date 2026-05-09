##                                      Healthcare Claims Lakehouse Platform


Enterprise-scale Databricks Healthcare Migration Accelerator built using PySpark, Delta Lake, ML, NLP, Streaming, REST APIs, Terraform, and Workflow Orchestration.


1. # *Project Overview*

This project demonstrates a complete end-to-end healthcare claims modernization platform using the Medallion Architecture (Bronze → Silver → Gold) on Databricks.

The platform simulates a real enterprise healthcare migration accelerator capable of:
* Multi-source healthcare ingestion
* Incremental ETL pipelines
* Data quality validation
* ML fraud detection
* NLP healthcare analytics
* Workflow orchestration
* Real-time streaming
* Dashboarding and reporting
* Infrastructure as Code (Terraform)
* Governance with Unity Catalog



# *2. Architecture*

# Medallion Data Flow
Source Systems

           ↓

Bronze Layer (Raw Ingestion)

           ↓

Silver Layer (Cleaned \& Standardized)

           ↓

Gold Layer (Business Aggregations)

           ↓

Dashboards / ML / APIs / Analytics


## *3. Technology Stack*
| Category               | Technologies                   |

| ---------------------- | ------------------------------ |

| Cloud Analytics        | Databricks                     |

| Processing Engine      | Apache Spark / PySpark         |

| Storage                | Delta Lake                     |

| Query Engine           | Spark SQL                      |

| Machine Learning       | MLlib                          |

| NLP                    | Spark NLP                      |

| Workflow Orchestration | Databricks Workflows / Airflow |

| Infrastructure         | Terraform                      |

| Governance             | Unity Catalog                  |

| APIs                   | REST APIs                      |

| Streaming              | Structured Streaming           |

| Visualization          | Databricks Dashboards          |



# ***Key Features***

# 1. Bronze Layer Ingestion
* Raw healthcare claims ingestion
* Incremental loading framework
* Multi-source ingestion support
* Delta-based storage



# 2. Silver Layer Transformation
* Data cleansing
* Standardization
* Null handling
* Schema enforcement



# 3. Gold Layer Aggregation
* Business KPI generation
* Department-level metrics
* Dashboard-ready datasets



# 4. Data Quality Framework
* Null validations
* Duplicate detection
* Invalid record isolation
* Quality scoring engine
* Rejected records quarantine



# 5. Real ML Fraud Detection
* Logistic Regression model
* Fraud prediction scoring
* ML pipeline orchestration
* AUC evaluation metrics



# 6. Real NLP Healthcare Analytics
* Clinical text analysis
* NLP entity extraction
* Healthcare insight generation



# 7. Workflow Orchestration
* Master ETL workflow
* Audit logging
* End-to-end execution monitoring


# 8. Real-Time Streaming
* Streaming healthcare ingestion
* Near real-time processing pipeline



# 9. REST API Integration
* External healthcare API ingestion
* API-driven pipeline integration


# 10. Terraform Infrastructure as Code
* Databricks infrastructure automation
* Reproducible environment provisioning


# 11. Unity Catalog Governance
* Centralized governance
* Table-level security simulation
* Metadata management


# *4. Project Structure*
01_Bronze_Ingestion

02_Silver_Transformation

03_Gold_Aggregation

04_Validation_Framework

05_AI_SQL_Converter

06_Dashboards

07_ML_Models

08_Architecture

09_Datasets

10_ETL_Automation

11_Workflow_Orchestration

12_Incremental_Loading

13_CICD_Deployment

14_UnityCatalog_Governance_Framework

15_Real_ML_AI

16_Real_NLP_Healthcare

17_REST_API_Integration

18_Airflow_Orchestration

19_Multi_Source_Ingestion

20_Real_Time_Streaming

21_Terraform_Infrastructure

22_Data_Quality_Framework

23_GitHub_Deployment_And_Documentation


# *5. Dashboarding*
The platform includes enterprise healthcare analytics dashboards with:
* Claims KPIs
* Department-level analytics
* Coverage metrics
* Quality metrics
* Aggregation insights


# *6. Machine Learning Output*
The ML pipeline performs healthcare fraud detection using Logistic Regression and generates prediction datasets stored in the Gold layer.

Example outputs:
* Fraud prediction labels
* Prediction probabilities
* AUC evaluation score


# *7. Data Quality Validation*
Validation framework capabilities:
* Invalid record detection
* Duplicate detection
* Data quality scoring
* Rejected records management

Outputs generated:
* "data_quality_metrics"
* "rejected_claims_records"


# *8. Workflow Execution*
Master ETL workflow includes:

Bronze Ingestion

→ Silver Transformation

→ Gold Aggregation

→ Validation Engine

→ ML Fraud Detection

→ AI SQL Modernization



# *9. Screenshots*
Project screenshots available in:
/screenshots

Architecture diagrams available in:
/architecture


# *10. Future Enhancements*
* Real cloud deployment
* Kafka integration
* CI/CD automation pipelines
* Advanced ML models
* Real-time monitoring dashboards
* Healthcare FHIR integration


# **Author**
Likhith Mothukuri
Healthcare Data Engineering || Databricks || PySpark || AI/ML || Cloud Analytics


# **License**
This project is intended for educational, portfolio, and demonstration purposes.



