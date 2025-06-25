# Data-analyst-Rizwan
📊 Descriptive Analysis
Project Title: Analyzing Business Licensing Trends in the Animal Services Sector
Location: City of Vancouver, Canada

📝 Project Description
This project performs a descriptive analysis of the Business Licenses dataset from Vancouver’s Open Data portal, focusing on the Animal Services sector. The objective is to uncover insights about license activity, geographic distribution, business sizes, and temporal trends that support policy decisions and operational efficiency.

🎯 Objective
To understand the behavioral patterns and trends in business licensing—specifically in the animal services category—by summarizing and visualizing transactional data, and presenting actionable recommendations for urban planning and decision-making.

📂 Dataset
The dataset consists of:

Business Name & ID

Business Subtype (e.g., grooming, boarding)

License Status (Active, Expired, Pending)

Location and Neighborhood

Number of Employees

Year of Operation
🧰 Technologies Used
Service	Purpose
Amazon S3	Data storage (raw, clean, curated)
AWS Glue	ETL pipelines, DataBrew for profiling
Amazon Athena	SQL queries on S3 datasets
AWS KMS	Encryption for secure data storage
IAM	Role-based access control
CloudWatch	Monitoring ETL jobs and alarms
CloudTrail	Auditing and activity logging
🔄 Workflow Summary

<img width="452" alt="image" src="https://github.com/user-attachments/assets/70f05d01-b0b1-43a3-b4ab-1b2810313c9d" />

🔍 Methodology
Step 1: Data Ingestion

Pulled raw data from Vancouver Open Data portal.

<img width="452" alt="image" src="https://github.com/user-attachments/assets/d40a8b86-0609-4d7d-b3e5-d6cb37a7a758" />

Stored in Amazon S3 (business-raw-bin bucket).

Step 2: Data Profiling & Cleaning

Performed using AWS Glue.

Addressed nulls, standardized column names, corrected data types.

<img width="452" alt="image" src="https://github.com/user-attachments/assets/69318c43-b5a0-4d9e-8322-b0ed1082f229" />

<img width="452" alt="image" src="https://github.com/user-attachments/assets/b2d53d52-ead2-430e-8f81-2b5d1ef46834" />

out put was saved to clean and curated buckets created in S3 layers

<img width="452" alt="image" src="https://github.com/user-attachments/assets/30d3a38a-5e2d-4679-a0de-aa1c125b5f9b" />

Step 3: Data Cataloging

AWS Glue Crawler created schema and table metadata by using athena query.

<img width="452" alt="image" src="https://github.com/user-attachments/assets/9efa0dbe-d75b-4638-9784-2110a74bb049" />

Step 4: Data Summarization

Used Visual ETL to apply filters, aggregation, and transformation.

Metrics stored in system/user buckets.

<img width="452" alt="image" src="https://github.com/user-attachments/assets/4dae1cee-b6fb-4db2-ae59-d9489233128e" />

📊 Project 2: AWS Data Analytics Platform – City of Vancouver
🔍 Overview
A cloud-native platform developed for analyzing Employee Remuneration and Expenses from the City of Vancouver. Built using AWS services to ensure security, encruption and decryprion, Quality Check.

Step 5: Visualization

Created metrics dashboards for business density and activity by location, status, and time.

<img width="452" alt="image" src="https://github.com/user-attachments/assets/83a4edb5-be09-4b89-ac96-7ad533b3df99" />

the default encryption is enabled for the curated bucket.

<img width="452" alt="image" src="https://github.com/user-attachments/assets/acf9f024-f260-4753-854b-b6d28eae41ad" />

<img width="452" alt="image" src="https://github.com/user-attachments/assets/2cff8a09-5d0b-486b-aa8d-f5c7e7fdfae7" />


Step 6: Security & Governance

Implemented encryption via KMS.

<img width="452" alt="image" src="https://github.com/user-attachments/assets/65a6a0e3-cf40-4bef-b831-73384ecbfac2" />

<img width="452" alt="image" src="https://github.com/user-attachments/assets/cb28280a-03c8-4247-9e2b-56f5aae9697b" />

<img width="452" alt="image" src="https://github.com/user-attachments/assets/12140d12-0ddc-4f86-901f-d7ccba4fa107" />

Enabled versioning, default encryption, and cross-region replication in S3.

<img width="452" alt="image" src="https://github.com/user-attachments/assets/ec46e4fb-3f3a-4cdd-ae6a-80053a3cb719" />

Validated with CloudTrail and Visual ETL data quality checks.

Step 7: Monitoring

Used CloudWatch dashboards and alarms for real-time status.

<img width="452" alt="image" src="https://github.com/user-attachments/assets/672aa76d-10af-4ac2-9b0b-8cf1a003ca38" />

Created activity logging trail via CloudTrail for full visibility.

<img width="452" alt="image" src="https://github.com/user-attachments/assets/7d43c7e6-2ae3-4261-be1b-879ebfc4937a" />

 step 8: Cost Estimation
 
<img width="452" alt="image" src="https://github.com/user-attachments/assets/58d4c1cc-431b-45ca-8a51-cfbb0b94de64" />

📦 Deliverables

Cleaned and transformed datasets

Data governance and security configurations

Real-time monitoring dashboards

Summary report with findings and recommendations

The project is a success and effective in illustrating how the AWS cloud services can be used in converting municipal data into usable information. Taxpayers are an important stakeholder who can improve its promises to accountability, efficient operations, and evidence-based decision-making in the City of Vancouver by examining compensation trends and establishing monitoring and governance processes.

Project 3: AWS Cloud Portfolio Demonstration (Simulated Case Study)
☁️ AWS Case Study Summaries

1️⃣ AWS Deployment & Service Models

Used AWS cloud for scalable, centralized analytics. Services like S3 (data lake), Glue (ETL), and IAM (access control) supported the serverless and fault-tolerant design.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/b7b04117-597f-46fd-af41-21781466be6d" />

<img width="452" alt="image" src="https://github.com/user-attachments/assets/31858ec5-2ecb-44cc-aefb-212dbe59f248" />

<img width="452" alt="image" src="https://github.com/user-attachments/assets/52b3226c-1bc7-4731-a8f0-70cb1f4a198e" />

Explanation: This module laid the foundation for understanding cloud computing by comparing traditional and cloud models. It emphasized the benefits of elasticity, scalability, and cost-effectiveness. The deployment models helped distinguish the environments in which AWS services operate, while the service models clarified the levels of control and responsibility. Scoring 100% in the module demonstrates a strong grasp of AWS’s layered architecture and deployment strategies.

2️⃣ AWS Cost Analysis

Used AWS Pricing Calculator to estimate costs for ETL and storage. Balanced high-DPU performance with budget limits to maintain cost-efficiency.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/f95273fb-2001-4eb4-b7f3-ea112a20141d" />

Description: This module presented financial planning in AWS. The case study of TCO explained why the cloud provides savings in the long run. The AWS Pricing Calculator gave practical experience in calculating cost of services, whereas the Support Plans comparison demonstrated contrast between Basic Support, Developer Support and Business Support. A score of 100 indicates thorough awareness of blogs of AWS pricing and financial management instruments.

3️⃣ AWS Global Infrastructure

Deployed services across regions and AZs. Enabled cross-region S3 replication for disaster recovery and data availability.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/2436179a-f485-4bd0-ae10-e35737539a03" />

Discussion: This lesson explored the presence of AWS worldwide. The case study showed that through the distribution of the data centers, performance, security and even disaster recovery was improved. It assisted in learning how Regional Edge Caches, Edge Locations and Regions can be used to deliver low latency and high availability. The maximum score 100 shows that you know everything about the AWS world infrastructure.

4️⃣ AWS IAM
Created custom IAM roles for fine-grained access to Glue, S3, and KMS. Ensured least-privilege model and policy compliance.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/9b0d9bc3-e27a-4219-b201-4f3cca90828a" />

Description: This module was concerned with access to AWS resources security. The shared responsibility model explains what will be handled by AWS and what can be handled by a user. The IAM lab provided realistic experience about how to create users, groups, and policies. An excellent score of 100 implies effective knowledge of best practices of implementing security on AWS.

5️⃣ AWS VPC

Configured isolated network environments with subnets, route tables, and internet gateways to protect ETL pipelines and data transfer.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/1526b0ca-68fc-4852-b097-1306e99bcf60" />

Explaination: This lab has demonstrated the process of creating a Virtual Private Clouds omitting subnets, route tables and gateways. It focused on safe-to-network, isolation and traffic management in AWS. A score of 100 means mastery of the designing and configuration of secure virtual networks.

6️⃣ AWS Lambda

Used Lambda for automating post-processing actions and notifying users upon job completion without maintaining servers.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/4df7136d-1038-44b0-889c-d7e321c833ea" />

Rationale: The functionality of serverless computing via AWS Lambda was discussed by the module. The case study scripted the roll out of functions, which are triggered but without server provisioning. A mark of 90 percent shows that you have a good knowledge of event-driven architecture and the execution of functions in the cloud.

7️⃣ AWS EBS

Attached EBS volumes to EC2 instances for persistent storage in test environments, enabling high-speed batch processing.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/35d34b11-f4e7-4cf8-a509-1bbc4c58eb31" />

Explanation: In the lab, the student was going to create, mount and restore EBS volumes. It emphasized on the significance of tenacious and long-lived block storage of EC2 instances. The 100 percent rating reflects the proficiency in volume lifecycle management of EBS and storage arrangement.

