# Data-Analyst-Shubham

**Data Analytics Projects on AWS Cloud**

This repository highlights my experience designing and implementing AWS Cloud data analytics platforms. The projects include:

**UCW Registrar Team** – Automating and optimizing student enrollment and withdrawal workflows.

**City of Vancouver** – Building a robust data analytics platform for managing and analyzing city property tax data.

Each project is categorized into specific analysis phases: Exploratory Data Analysis, Descriptive Analysis, Diagnostic Analysis, Data Wrangling, and Data Quality Control, with supporting visuals and workflows.

**Project 1: UCW Registrar Team**

This project focused on automating data workflows related to student enrollments and withdrawals, improving the efficiency of managing student data for the Registrar’s Office.

**1. Exploratory Data Analysis (EDA)**
   - Conducted an in-depth exploration of student enrollment and withdrawal records to identify trends and patterns in academic terms.
   - Utilized **AWS Glue** to organize and catalog data from various sources, including real-time data on student admissions and withdrawals.
   - Used **AWS Athena** to perform initial data profiling, identifying enrollment period peaks and withdrawal reasons trends.
   - **Amazon S3** was used as the primary storage for the datasets related to student enrollments and withdrawals.

![EDA Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/main/images/Week%202%20CP%201.png)
![EDA Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/main/images/Week%202%20CP%202.png)
![EDA Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/main/images/Week%203%20CP%201.png)


**2. Descriptive Analysis**
   - Generated detailed statistics on enrollment numbers, withdrawal rates, and trends over different semesters.
   - Used **AWS Athena** to analyze student movements across different courses and departments, summarizing the most common reasons for withdrawal.
   - Created regular reports for the Registrar team that provided insights into course enrollment rates, highlighting departments with higher-than-average withdrawals.
Screenshot: AWS Athena SQL Queries for descriptive statistics

**3. Diagnostic Analysis**
   - Investigated issues related to data inconsistencies in student withdrawal records, ensuring that all records were complete and accurate.
   - Used **AWS CloudWatch** to monitor and log data flows, helping to identify bottlenecks or errors in the data processing pipeline.
   - Debugged discrepancies in enrollment numbers by cross-referencing student records with academic department data in **AWS Glue**.
Screenshot: AWS CloudWatch logs for monitoring data flows

**4. Data Wrangling**
   - Automated the transformation of raw enrollment and withdrawal data into a standardized format, making tracking student changes across terms easier.
   - Developed ETL pipelines using **AWS Glue Studio** to ensure seamless integration of student data from various sources, including the university’s internal databases and external data systems.
   - **AWS Lambda** was used to trigger specific data transformations and handle real-time data updates related to enrollments and withdrawals.
   - All cleaned and processed data was securely stored in **Amazon S3** for further analysis and reporting.
Screenshot: AWS Glue Studio ETL pipeline for data transformation

**5. Data Quality Control**
   - Implemented quality control measures in **AWS Glue** to validate data consistency, ensuring that all student enrollment and withdrawal records were up-to-date.
   - Built error-checking mechanisms to detect anomalies, such as duplicate withdrawals or incorrect enrollment statuses, triggering automated alerts for corrections.
   - Established periodic data audits to continuously monitor the health of the student data and ensure that enrollment and withdrawal data were accurate and actionable for decision-makers.
Screenshot: AWS Glue error-checking mechanism for data quality control

**6. Data Security and Compliance**
   - Highlight how data was securely managed and stored using **Amazon S3** with appropriate access controls and encryption policies, ensuring the security of sensitive student data.
   - Discuss any measures taken to comply with regulatory requirements for handling sensitive data, such as encryption in transit and at rest.
Screenshot: AWS S3 security configurations

**7. Backup and Disaster Recovery**
   - Highlight how **AWS S3** was leveraged to ensure reliable backups of critical datasets, such as regular backups of student enrollment data.
   - Mention any disaster recovery protocols or procedures you set up to recover data in case of system failure or corruption.
Screenshot: Backup configurations and recovery protocols in S3





