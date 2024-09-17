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
   - Used **AWS Athena** to analyze student movements across different courses and departments, calculating the enrollment rate.
   - Created regular reports for the Registrar team that provided insights into course enrollment rates, highlighting departments with higher-than-average withdrawals.
   - Used **AWS EC2** for information sharing and publishing the reports.
     
![DA Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/main/images/Week%204%20CP%201.png)
![DA Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/main/images/Week%204%20WA%204.png)
![DA Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/main/images/Week%204%20WA%206.png)

**3. Diagnostic Analysis**
   - Investigated issues related to data inconsistencies in student withdrawal records, ensuring that all records were complete and accurate.
   - Used **AWS CloudWatch** to monitor and log data flows, helping to identify bottlenecks or errors in the data processing pipeline.

![DA Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/main/images/Week%209%20CP%201.png)

**4. Data Wrangling**
   - Automated the transformation of raw enrollment and withdrawal data into a standardized format, making tracking student changes across terms easier.
   - Developed ETL pipelines using **AWS Glue Studio** to ensure seamless integration of student data from various sources, including the university’s internal databases and external data systems.
   - **AWS Lambda** was used to trigger specific data transformations and handle real-time data updates related to enrollments and withdrawals.
   - All cleaned and processed data was securely stored in **Amazon S3** for further analysis and reporting.

![DW Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/main/images/DP%201%20-%20ETL%20pipelines%20-%20Draw%201.png)
![DW Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/main/images/DP%201%20-%20ETL%20pipelines%20-%20Draw%202.png)
![DW Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/main/images/DP%201%20-%20ETL%20pipelines%20-%20Draw%203.png)
![DW Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/main/images/DP%201%20-%20ETL%20pipelines%20-%20AWS%20Glue.png)


**5. Data Quality Control**
   - Implemented quality control measures in **AWS Glue** to validate data consistency, ensuring that all student enrollment and withdrawal records were up-to-date.
   - Built error-checking mechanisms to detect anomalies, such as duplicate withdrawals or incorrect enrollment statuses, triggering automated alerts for corrections.
   - Used **AWS CloudTrails** for loging user information
   - Established periodic data audits to continuously monitor the health of the student data and ensure that enrollment and withdrawal data were accurate and actionable for decision-makers.
   - Used **AWS KMS** for encrpyting the data
   - Used S3 replication rules for data backup

![DQC Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/main/images/Week%208%20CP%201.png)
![DQC Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/main/images/Week%209%20CP%203.png)
![DQC Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/main/images/Week%207%20CP%201.png)
![DQC Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/main/images/Week%207%20CP%202%20.png)


**6. Predictive Analysis**
   - Used **Amazon SageMaker** for object detection, which can help analyze the documents submitted by students at the registrar's office, for example, detecting students' study permit expiry date. 

![PA Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/main/images/Week%2010%20CP.png)








