# Data-Analyst-Shubham

**Data Analytics Projects on AWS Cloud**

This repository highlights my experience designing and implementing AWS Cloud data analytics platforms. The projects include:

**Project 1**: **UCW Registrar Enrolment and Withdrawal**


This project focused on automating the enrolment and withdrawal processes at the University Canada West (UCW). By leveraging many AWS services, such as Glue, EC2, and CloudTrail, the project improved the efficiency and accuracy of student record management. Key tasks included data wrangling, exploratory analysis of enrolment trends, and implementing data quality control measures to ensure compliance and accuracy in student records. This automation reduced manual errors and provided real-time insights into enrolment patterns.

**Exploratory Data Analysis (EDA)**

**Project Description:** The UCW Registrar's office faced challenges managing student enrolment and withdrawal records due to manual processing. This project focused on automating these processes and performing exploratory data analysis to identify trends and improve decision-making.


**Project Title:** Exploratory Analysis of UCW Enrolment and Withdrawal Patterns


**Objective:** To explore student enrolment and withdrawal trends using AWS services to uncover insights that help UCW optimize resources and improve student retention strategies.


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
   2.	**Descriptive Statistics:**
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

![UCW Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/refs/heads/main/images/Picture1.png)
![UCW Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/refs/heads/main/images/Picture2.png)
![UCW Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/refs/heads/main/images/Picture3.png)

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
         - AWS Athena is used to query the table and data export.
   4.	**Insights and Findings:**
         - Based on the descriptive analysis, the average enrollment rate for 2022 and 2024 is less than that of other years.
   5.	**Recommendations:**
         - The drop in the enrollment rate needs further analysis to find the root cause of the fewer enrollments during 2022 and 2024. 


**Tools and Technologies:**
- **AWS Glue**: For data processing and cleaning
- **AWS EC2**: For statistical analysis, information processing, and visualization
- **AWS Athena**: For querying the data


**Deliverables:**
- A report summarizing enrolment trends, including key statistics and visual summaries.


**Timeline:**
- Completed in 4 weeks.

![UCW Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/refs/heads/main/images/Picture5.png)
![UCW Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/refs/heads/main/images/Picture6.png)
![UCW Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/refs/heads/main/images/Picture7.png)
![UCW Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/refs/heads/main/images/Picture8.png)
![UCW Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/refs/heads/main/images/Picture19.png)
![UCW Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/refs/heads/main/images/Picture9.png)
![UCW Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/refs/heads/main/images/Picture10.png)
![UCW Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/refs/heads/main/images/Picture11.png)
![UCW Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/refs/heads/main/images/Picture12.png)

________________________________________
**Diagnostic Analysis**


**Project Description:** The diagnostic analysis focused on identifying the underlying causes of high withdrawal rates in specific courses and academic sessions.


**Project Title:** Diagnostic Analysis of UCW Withdrawal Rates


**Objective:** Identify the key factors driving high withdrawal rates at UCW, focusing on student demographics and course difficulty.


**Background:** Some courses at UCW had higher-than-average withdrawal rates, prompting an investigation into potential causes.


**Scope:** The analysis focused on diagnosing the causes of withdrawals by correlating withdrawal data with student demographics and academic calendar timing.


**Dataset:**
- Student demographics
- Course enrolment and withdrawal records


**Methodology:**
   1.	**Data Collection:**
         - AWS Glue was used to gather relevant data for analysis.
   2.	**Correlation Analysis:**
         - AWS EC2 ran a correlation analysis to identify relationships between course difficulty and student withdrawals.
   3.	**Auditing:**
         - AWS CloudTrail was used to track and audit changes to student records for compliance.


**Tools and Technologies:**
- **AWS Glue:** For data collection
- **AWS EC2:** For correlation analysis
- **AWS CloudTrail:** For auditing


**Deliverables:**
- A diagnostic report with recommendations for reducing withdrawal rates based on key findings.


**Timeline:**
- Completed in 3 weeks.

![UCW Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/refs/heads/main/images/Picture13.png)

________________________________________
**Data Wrangling**


**Project Description:** Data wrangling was necessary to ensure all student records were clean, consistent, and ready for further analysis.


**Project Title:** Data Wrangling for UCW Enrolment Data


**Objective:** Clean and organize student enrolment and withdrawal data for analysis.


**Background:** Due to inconsistencies in student data, a data wrangling phase was required to clean and standardize the records.


**Scope:** This phase focused on cleaning, standardizing, and consolidating student records.


**Dataset:**
- Raw enrolment and withdrawal records
- Course registration data


**Methodology:**
   1.	**Data Cleaning:**
         - AWS Glue was used to clean student data, remove duplicates, and handle missing values.
   2.	**Data Transformation:**
         - The cleaned data was stored in Amazon S3 for further analysis.


**Tools and Technologies:**
- **AWS Glue**: For data cleaning
- **Amazon S3**: For data storage


**Deliverables:**
- A clean and consolidated dataset ready for analysis.


**Timeline:**
- Completed in 1 week.

![UCW Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/refs/heads/main/images/Picture14.png)

________________________________________
**Data Quality Control**


**Project Description:** Ensuring data quality was critical to maintaining the integrity of UCW’s student records. This phase focused on implementing quality control measures to audit and validate student data.


**Project Title:** Data Quality Control for UCW Registrar


**Objective:** Implement data quality control measures to ensure the accuracy of student enrolment records.


**Background:** Given the reliance on manual data entry in the past, it was important to audit and validate student records to ensure accuracy.


**Scope:** This phase included auditing student records, validating data accuracy, and ensuring compliance with university policies.


**Dataset:**
- Enrolment and withdrawal records


**Methodology:**
   1.	**Auditing:**
         - AWS CloudTrail was used to audit changes made to student records.
   2.	**Validation:**
         - AWS Glue ran validation scripts to ensure data accuracy and privacy.
   3.	**Encryption:**
         - AWS KMS created the key to encrypt the S3 bucket for data protection.
   4.	**Replication:**
         - AWS S3 replication rule for data backup.
   5.	**Monitor and Control:**
         - AWS CloudWatch to monitor and control resource utilization.


**Tools and Technologies:**
- **AWS CloudTrail**: For auditing
- **AWS Glue**: For data privacy and accuracy
- **AWS KMS**: Encryption key
- **AWS S3**: For replication rule
- **AWS CloudWatch**: To monitor and control AWS resources


**Deliverables:**
- A report summarizing data quality results and ongoing monitoring systems.


**Timeline:**
- Completed in 4 weeks.

![UCW Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/refs/heads/main/images/Picture15.png)
![UCW Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/refs/heads/main/images/Picture16.png)
![UCW Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/refs/heads/main/images/Picture18.png)
![UCW Process](https://raw.githubusercontent.com/ShubhamSharmaMBA/Data-Analyst-Shubham/refs/heads/main/images/Picture17.png)

________________________________________
________________________________________

**Project 2**: **City of Vancouver Property Tax Report Generation**


The City of Vancouver's property tax department faced delays and errors in manual report generation. This project automated the collection and reporting of property tax data using AWS services like Glue, EC2, and CloudTrail. Key activities involved cleaning and consolidating tax payment records, conducting diagnostic analysis of delinquent payments, and implementing data quality control to ensure accurate and timely report generation. The project improved tax collection efficiency and provided actionable insights into payment trends.


**Exploratory Data Analysis (EDA)**


**Project Description:** The City of Vancouver struggled with manual property tax report generation, leading to delays and errors. This project focused on automating tax report generation and performing exploratory data analysis to identify trends in tax payments.

**Project Title:** Exploratory Analysis of Vancouver Property Tax Payments

**Objective:** Perform exploratory analysis on property tax payment data to uncover delinquency and payment compliance patterns.

**Background:** The City of Vancouver’s property tax department relied on manual processes for generating reports, resulting in delays. The project aimed to streamline report generation using AWS and uncover insights on payment behavior.

**Scope:** This project involved analyzing historical tax payment data to identify payment compliance and delinquency trends.

**Dataset:**
- Property IDs
- Tax Payment Records
- Delinquency Data

**Methodology:**
   1. **Data Collection and Cleaning**:
      - AWS Glue was used to clean and prepare tax payment data.
      - Data was stored in Amazon S3 for analysis.
   2. **Exploratory Analysis**:
      - AWS EC2 was used to run scripts to analyze tax payment trends and delinquency rates.

**Tools and Technologies:**
- **AWS Glue**: For ETL
- **AWS EC2**: For analysis
- **Amazon S3**: For data storage

**Deliverables:** 
- A report detailing tax payment trends and delinquency rates.

**Timeline:**
- Completed in 2 weeks.

________________________________________

**Descriptive Analysis**

**Project Description:** Descriptive analysis provided insights into overall tax payments and delinquency patterns across Vancouver’s districts.

**Project Title:** Descriptive Analysis of Vancouver Property Tax Payments

**Objective:** Summarize key tax payment statistics to identify high-risk regions and delinquency patterns.

**Background:** The City of Vancouver needed to understand payment compliance across various districts to improve tax collection strategies.

**Scope:** This phase involved summarizing tax payment data by district and identifying delinquency rates.

**Dataset:**
- Tax payment history


**Methodology:**
   1. **Data Aggregation**:
         - AWS Glue was used to aggregate payment data across districts.
   2. **Statistical Analysis**:
         - AWS EC2 was used to calculate delinquency rates and payment compliance.
   3.	**Data Visualization:**
         - AWS EC2 is for the general server, and the web server is for information sharing and data visualization.
         - AWS Athena is used to query the table and data export.
   4.	**Insights and Findings:**
         - Based on the descriptive analysis, the average current land value for strata decreased in 2024 compared to 2023
   5.	**Recommendations:**
         - The average current land value drop needs further analysis to find the root cause of the average price drop in 2024 for Strata Legal Type. 

**Tools and Technologies:**
- **AWS Glue**: For data aggregation
- **AWS EC2**: For analysis
- **AWS Athena**: For querying the data

**Deliverables:**
- A report summarizing tax payments and delinquency patterns with actionable insights.

**Timeline:**
- Completed in 4 weeks.

________________________________________

**Diagnostic Analysis**


**Project Description:** Diagnostic analysis was conducted to investigate the causes behind delayed or missing tax payments in specific regions.

**Project Title:** Diagnostic Analysis of Vancouver Property Tax Delinquencies

**Objective:** Diagnose the underlying factors behind delayed property tax payments in Vancouver.

**Background:** The City of Vancouver experienced high delinquency rates in specific areas, prompting an investigation to uncover the causes.

**Scope:** This phase identified correlations between property type, location, and payment delays.

**Dataset:**
- Delinquency records
- Property data

**Methodology:**
   1. **Correlation Analysis**:
         - AWS EC2 ran diagnostic scripts to identify trends in delinquent payments.
   2. **Auditing**:
         - AWS CloudTrail was enabled to monitor and audit access to payment records.


**Tools and Technologies:**
- **AWS EC2**: For diagnostic analysis
- **AWS CloudTrail**: For auditing

**Deliverables:**
A report outlining the causes of delinquent payments, with recommendations for improving compliance.

**Timeline:**
- Completed in 3 weeks.

________________________________________

**Data Wrangling**

**Project Description**: Property tax data needed to be cleaned and standardized before generating automated reports. This phase focused on data wrangling to ensure accuracy and consistency.

**Project Title**: Property Tax Data Wrangling for Reporting

**Objective:** Clean and standardize property tax records to ensure accurate report generation.

**Background:** The City of Vancouver’s property tax data contained inconsistencies, necessitating a data wrangling phase before generating reports.

**Scope:** This phase involved cleaning and consolidating property tax records.

**Dataset:**
- Property tax payment records

**Methodology:**
   1. **Data Cleaning**:
         - AWS Glue was used to clean and standardize the data for further processing.
   2. **Data Transformation**:
         - The cleaned data was stored in Amazon S3 for further analysis.


**Tools and Technologies:**
 - **AWS Glue**: For data cleaning
 - **Amazon S3**: For data storage

**Deliverables:**
- A clean, well-structured dataset ready for automated report generation.

**Timeline:**
- Completed in 1 week.

________________________________________

**Data Quality Control**

**Project Description**: Ensuring the accuracy of tax data was essential to the City of Vancouver’s tax report generation process. This phase focused on implementing data quality control measures.

**Project Title**: Ensuring Data Integrity in Property Tax Reports

**Objective**: Implement data quality control to ensure the accuracy and reliability of property tax reports.

**Background**: The City of Vancouver’s tax data required auditing and validation to ensure accuracy.

**Scope**: This phase included validating property tax records and auditing any changes.

**Dataset**:
- Property tax records

**Methodology:**
   1. **Auditing**:
         - AWS CloudTrail was used to monitor changes to property tax records.
   2. **Validation**:
         - AWS EC2 ran validation scripts to check for discrepancies.
   3.	**Encryption:**
         - AWS KMS created the key to encrypt the S3 bucket for data protection.
   4.	**Replication:**
         - AWS S3 replication rule for data backup.
   5.	**Monitor and Control:**
         - AWS CloudWatch to monitor and control resource utilization.


**Tools and Technologies:**
- **AWS CloudTrail**: For auditing
- **AWS Glue**: For data privacy and accuracy
- **AWS KMS**: Encryption key
- **AWS S3**: For replication rule
- **AWS CloudWatch**: To monitor and control AWS resources

**Deliverables:**
- A data quality report ensuring accuracy in property tax records.

**Timeline:**
- Completed in 3 weeks.

________________________________________



