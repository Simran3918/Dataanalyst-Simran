# Descriptive Analysis 
## Project Description: Descriptive Analysis of Real Estate Business License. 
## Project Title: Analyzing Business Licenses in the Real Estate Sector
## Objective: 
The purpose of this project is to explain and summarize the results of business license data in the real estate industry. Through a quick overview of important characteristics of the dataset, analysis of the trends and generation of the insights, the project will have the purpose of giving useful information to stakeholders and governmental agencies to provide understanding of licensing tendencies and real estate businesses distribution in different regions.
## Dataset: The dataset contains records of real estate business licenses for the year 2023 & 2024 with the following key features:
- FOLDERYEAR: The year of the license.
- LicenceRSN: Unique identifier for each license.
- LicenceNumber: License number.
- LicenceRevisionNumber: Revision number of the license.
- BusinessName: Name of the business.
- Status: Status of the license (e.g., Issued, Inactive).
- IssuedDate: Date the license was issued.
- ExpiredDate: License expiration date.
- BusinessType: Type of business (e.g., Real Estate Services).
- Location Details:Unit, UnitType, House, Street, City, Province, Country, 
- PostalCode: Address details of the business.
- LocalArea: The local area where the business is located.
- NumberofEmployees: Number of employees in the business.
- ExtractDate: Date when the data was extracted.
## Methodology:
## 1. Data Collection and Preparation:
- Data Source: The dataset for Real estate business license applications for the years 2023 and 2024 was collected from publicly available City of Vancouver records.
Tools Used:
- Amazon S3: The raw and cleaned datasets were stored in S3 buckets for easy access and querying.
- AWS Glue DataBrew: Data cleaning and preparation were performed to handle missing values, correct data types, and remove duplicates.
- Amazon Athena: The dataset was queried using SQL to prepare for analysis.
## Data Cleaning: 
- Addressed missing values (e.g., missing license expiration dates).
- Removed duplicates and corrected inconsistent data types (e.g., converting dates to a standard format).
## 2. Descriptive Statistics:
## Key Metrics Calculated:
- Number of Licenses Issued: Total count of Real Estate Business License issued each year.
- License Status Breakdown: Distribution of licenses by status (Issued or Inactive).
## 3. Data Visualization:
Visual representations were created to summarize the descriptive statistics:
-	Time-Series Graph: Shows the number of Real Estate Business License issued each month in 2023 and 2024, highlighting trends in business activity.
-	Pie Chart: Represents the distribution of Real Estate Business License statuses (e.g., Isssued, inactive,).
-	Bar Chart: Compares the total license fees paid by Real Estate Business License based on the number of employees (for 2024 & 2023).
## 4. Customer Segmentation and Analysis:
Although not directly related to customer purchases, Real Estate Business License are segmented based on:
- Size (Employee Count): To do this, they further sorted Real Estate Business License based on the number of employees and looked at the difference between large versus small consulting firms in terms of license status and fee paid.
- Status Trends: Displayed the fluctuations of the license status over time and determined the specific time points of increased and low business activity and their closures.
## 5. Insights and Findings:
- Peak Licensing Periods: It can be observed that there is a rather high number of licenses issued during the first quarter of 2023 and the second half of 2024, which fits Real Estate Business License phases. 
- License Expiration and Closure Trends: Most of the firms that got licenses in 2023 had complied by the time of early 2024 meaning that there is higher turnover of consultant. 
- Fee Insights: The license fees paid by the consulting firms at 2024 were high especially for those with many employees on their payroll. Nevertheless, there were many small firms which still form the majority of issued licenses.
## 6. Recommendations:
Based on the descriptive analysis, the following recommendations were made:
- Support for Small Businesses: The City of Vancouver may wish to offer further assistance to SME consulting firms in an effort to bolster the current low survival rates. 
- Targeted Marketing and Services: The licensing department could in the future offer better targeted service and marketing of the licenses depending on the size of the Real Estate Business License in order to enhance the renewal rates.
- Policy Adjustments: Revise fee schedules to be fair and encourage non-renewal of contracts to extend the beneficial timeframe of Real Estate Business License activity.

## Tools and Technologies:
 
AWS Services Used:
1. Amazon S3: To store the raw, processed, and cleaned datasets.
2. AWS Glue DataBrew: To automate the cleaning and preparation of the dataset.
3. Amazon Athena: To run SQL queries and calculate descriptive statistics for analysis.
5. AWS Lambda: For automating ETL (Extract, Transform, Load) tasks in data pipelines.
6. AWS Glue Data Catalog: To manage and organize metadata for easy querying with Athena.
7. AWS Identity and Access Management (IAM): For secure access control.
8. AWS Key Management Service (KMS): To encrypt data stored in S3, ensuring security compliance.
   
## Deliverables:
## 1. Detailed Report:
An entire set of integrated materials that is used to provide an overview of the complete descriptive analysis flow, conclusions and data derived thereof. Provides data regarding the licenses’ distribution, Real Estate Business License statuses, licensing tendencies, and fees.
## 2. Visualizations and Dashboards:
   - Time-Series Graph: Monthly trend of license applications.
   - Pie Chart: Status distribution (active, inactive, gone out of business).
   - Bar Chart: Fee analysis based on employee count.
## 3. Presentation for Stakeholders:
An overview of the work done, main conclusions, and reference information in the form of tables and diagrams. This presentation has been designed with a view to helping the city officials and other stakeholders of Vancouver to better understand the Real estate services business environment and its implications and, in the process, act appropriately.

## Conclusion:
This paper aims at making a descriptive analysis of Real estate services business license applications in Vancouver which applies for the year 2023 and 2024. Licensing status, business statuses, and fee payments collected allow stakeholders to make informed decisions for the better organization of businesses and increased support of SMBs.
