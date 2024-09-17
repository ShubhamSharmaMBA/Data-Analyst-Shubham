# Data-Analyst-Shubham

**Data Analytics Projects on AWS Cloud**

This repository highlights my experience designing and implementing AWS Cloud data analytics platforms. The projects include:

**Project 1**

**UCW Registrar Enrolment and Withdrawal**


This project focused on automating the enrolment and withdrawal processes at the University Canada West (UCW). By leveraging many AWS services, such as Glue, EC2, and CloudTrail, the project improved the efficiency and accuracy of student record management. Key tasks included data wrangling, exploratory analysis of enrolment trends, and implementing data quality control measures to ensure compliance and accuracy in student records. This automation reduced manual errors and provided real-time insights into enrolment patterns.

**Exploratory Data Analysis (EDA)**

**Project Description:** The UCW Registrar's office faced challenges managing student enrolment and withdrawal records due to manual processing. This project focused on automating these processes and performing exploratory data analysis to identify trends and improve decision-making.


**Project Title:** Exploratory Analysis of UCW Enrolment and Withdrawal Patterns


**Objective:** To explore student enrolment and withdrawal trends using AWS services to uncover insights that help UCW optimize resources and improve student retention strategies**.


**Background:** Manual processing of enrolments and withdrawals at UCW was causing delays and errors. The university wanted to automate the data handling process and use exploratory data analysis to identify patterns in student behavior.


**Scope:** The project involved analyzing historical enrolment and withdrawal records to generate insights that could help the Registrar’s Office make informed decisions regarding academic offerings and resources.


**Dataset:**
- Student IDs
- Enrolment Dates
- Withdrawal Requests
- Course Registrations


**Methodology:**
   1.	**Data Collection and Preparation:**
         - AWS Glue was used to extract and clean student records.
         - Data was stored in Amazon S3 for analysis.
   3.	**Descriptive Statistics:**
         - AWS EC2 computed summary statistics on enrolment and withdrawal trends.
         - Visualization was done using EC2 Web Server to identify seasonal variations.

      
**Tools and Technologies:**
   - **AWS Glue**: For ETL tasks
   - **Amazon S3**: For data storage
   - **AWS EC2**: For General and Web Servers


**Deliverables:**
•	A comprehensive report on enrolment and withdrawal patterns, with visualizations for academic decision-making.


**Timeline:**
•	Completed in 2 weeks.

________________________________________
**Descriptive Analysis**


**Project Description:** A descriptive analysis of enrolment and withdrawal data was conducted to summarize student trends and behavior.


**Project Title:** Descriptive Analysis of UCW Enrolment and Withdrawal Statistics


**Objective:** Summarize key student enrolment and withdrawal data statistics to provide actionable insights.


**Background:** UCW needed to understand how enrolment and withdrawal rates varied across different academic sessions and departments to allocate resources efficiently.


**Scope:** This project phase summarized historical enrolment and withdrawal data by academic year and department.


**Dataset:**
- Enrolment records
- Withdrawal requests
- Demographic information


**Methodology:**
   1.	**Data Aggregation:**
         - AWS Glue was used to aggregate enrolment data over several years.
   2.	**Descriptive Statistics:**
         - AWS EC2 ran scripts to calculate key statistics, such as average enrolment per semester and withdrawal rates.
   3.	**Data Visualization:**
         - AWS EC2 is for the general server, and the web server is for information sharing and data visualization.
   4.	**Insights and Findings:**
         - Based on the descriptive analysis, the average enrollment rate for 2022 and 2024 is less than that of other years.
   5.	**Recommendations:**
         - The drop in the enrollment rate needs further analysis to find the root cause of the fewer enrollments during 2022 and 2024. 


**Tools and Technologies:**
- **AWS Glue**: For data processing and cleaning
- **AWS EC2**: For statistical analysis, information processing, and visualization


**Deliverables:**
- A report summarizing enrolment trends, including key statistics and visual summaries.


**Timeline:**
- Completed in 4 weeks.


________________________________________
Diagnostic Analysis
Project Description:
The diagnostic analysis focused on identifying the underlying causes of high withdrawal rates in specific courses and academic sessions.
Project Title:
Diagnostic Analysis of UCW Withdrawal Rates
Objective:
Identify the key factors driving high withdrawal rates at UCW, with a focus on student demographics and course difficulty.
Background:
Some courses at UCW had higher-than-average withdrawal rates, prompting an investigation into potential causes.
Scope:
The analysis focused on diagnosing the causes of withdrawals by correlating withdrawal data with student demographics and academic calendar timing.
Dataset:
•	Student demographics
•	Course enrolment and withdrawal records
Methodology:
1.	Data Collection:
o	AWS Glue was used to gather relevant data for analysis.
2.	Correlation Analysis:
o	AWS EC2 ran a correlation analysis to identify relationships between course difficulty and student withdrawals.
3.	Auditing:
o	AWS CloudTrail was used to track and audit changes to student records for compliance.
Tools and Technologies:
•	AWS Glue: For data collection
•	AWS EC2: For correlation analysis
•	AWS CloudTrail: For auditing
Deliverables:
•	A diagnostic report with recommendations for reducing withdrawal rates based on key findings.
Timeline:
•	Completed in 3 weeks.

________________________________________
Data Wrangling
Project Description:
Data wrangling was necessary to ensure all student records were clean, consistent, and ready for further analysis.
Project Title:
Data Wrangling for UCW Enrolment Data
Objective:
Clean and organize student enrolment and withdrawal data for analysis.
Background:
Due to inconsistencies in student data, a data wrangling phase was required to clean and standardize the records.
Scope:
This phase focused on cleaning, standardizing, and consolidating student records.
Dataset:
•	Raw enrolment and withdrawal records
•	Course registration data
Methodology:
1.	Data Cleaning:
o	AWS Glue was used to clean student data, remove duplicates, and handle missing values.
2.	Data Transformation:
o	The cleaned data was stored in Amazon S3 for further analysis.
Tools and Technologies:
•	AWS Glue: For data cleaning
•	Amazon S3: For data storage
Deliverables:
•	A clean and consolidated dataset ready for analysis.
Timeline:
•	Completed in 1 week.

________________________________________
Data Quality Control
Project Description:
Ensuring data quality was critical to maintaining the integrity of UCW’s student records. This phase focused on implementing quality control measures to audit and validate student data.
Project Title:
Data Quality Control for UCW Registrar
Objective:
Implement data quality control measures to ensure the accuracy of student enrolment records.
Background:
Given the reliance on manual data entry in the past, it was important to audit and validate student records to ensure accuracy.
Scope:
This phase included auditing student records, validating data accuracy, and ensuring compliance with university policies.
Dataset:
•	Enrolment and withdrawal records
Methodology:
1.	Auditing:
o	AWS CloudTrail was used to audit changes made to student records.
2.	Validation:
o	AWS Glue ran validation scripts to ensure data accuracy and privacy.
3.	Encryption:
o	AWS KMS created the key to encrypt the S3 bucket for data protection.
4.	Replication:
o	AWS S3 replication rule for data backup.
5.	Monitor and Control:
o	AWS CloudWatch to monitor and control resource utilization.
Tools and Technologies:
•	AWS CloudTrail: For auditing
•	AWS Glue: For data privacy and accuracy
•	AWS KMS: Encryption key
•	AWS S3: For replication rule
•	AWS CloudWatch: To monitor and control AWS resources
Deliverables:
•	A report summarizing data quality results and ongoing monitoring systems.
Timeline:
•	Completed in 4 weeks.




**6. Predictive Analysis**
   - Used **Amazon SageMaker** for object detection, which can help analyze the documents submitted by students at the registrar's office, for example, detecting students' study permit expiry date. 

![PA Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/main/images/Week%2010%20CP.png)













