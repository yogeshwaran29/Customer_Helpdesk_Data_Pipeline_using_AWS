# AWS_ETL_Pipeline-Helpdesk
An ETL Pipeline which ingests customer's help tickets and support logs data to AWS S3 using python and clean , transform that raw data using AWS Lambda and AWS Glue , Stores the processed data in AWS S3 and copy that data to AWS Redshift using AWS lambda , Automated by Events Notifications

---
## 🎯 **Objectives**

- **Automate data ingestion** from Careplus support logs and tickets into **AWS S3**.
- **Process and clean data** using **AWS Lambda** and **AWS Glue**.
- **Generate actionable insights** for support tickets, agent performance, and system logs.
- Provide a **dashboard** to visualize key metrics, including:
  - Ticket count and resolution times
  - Agent performance
  - System health and log-level analysis
  - Predictive insights for ticket escalations

---

## 🧰 **Tools & Technologies**

| **Tool / Service**         | **Purpose**                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| **AWS S3**                 | Storage for raw and processed data                                           |
| **AWS Lambda**             | Serverless compute for data processing (ETL)                                 |
| **AWS Glue**               | Managed ETL service for data cleaning and transformation                      |
| **AWS RedShift**           | Data warehouse for storing processed data                                    |
| **Amazon Athena**          | Querying processed data for ad-hoc analysis                                  |
| **Power BI**               | Dashboard visualization of key metrics                                       |
| **Python**                 | Scripting for Lambda and Glue functions                                      |
| **Pandas**                 | Data manipulation and transformation                                         |

---

## ✅ **Outcomes**

- 🏆 Real-time insights into ticket performance and agent productivity
- 🚀 Automated ETL pipeline for data processing and transformation
- 💡 Enhanced decision-making capabilities with actionable reports
- 🔐 Scalability and governance with **AWS Glue** and **Amazon RedShift**
