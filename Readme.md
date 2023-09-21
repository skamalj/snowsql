
## Domain 1.0: Snowflake Data Cloud Features and Architecture

### 1.1 Outline key features of the Snowflake Data Cloud.
>* Elastic Storage
>* Elastic Compute
>* Snowflake’s three distinct layers
>* Data Cloud/ Data Exchange/ Partner Network
>* Cloud partner categories

### 1.2 Outline key Snowflake tools and user interfaces.
>* Snowflake User Interfaces (UI)
>* Snowsight
>* Snowflake connectors
>* Snowflake drivers
>* SQL scripting
>* Snowpark
### 1.3 Outline Snowflake’s catalog and objects.
>* Databases
>* Schemas
>* Tables types
>* View types
>* Data types
>* User-Defined Functions (UDFs) and User Defined Table Functions (UDTFs)
>* Stored procedures
>* Streams
>* Tasks
>* Pipes
>* Shares
>* Sequences
### 1.4 Outline Snowflake storage concepts.
>* [Micro-partitions](https://docs.snowflake.com/en/user-guide/tables-clustering-micropartitions)
>* Types of column metadata clustering
>* Data storage monitoring
>* Search optimization service


## Domain 2.0: Account Access and Security
### 2.1 Outline security principles.
● Network security and policies
● Multi-Factor Authentication (MFA)
● Federated authentication
● Single Sign-On (SSO)
2.2 Define the entities and roles that are used in Snowflake.
● Outline how privileges can be granted and revoked
● Explain role hierarchy and privilege inheritance
2.3 Outline data governance capabilities in Snowflake.
● Accounts
● Organizations
● Databases
● Secure views
● Information schemas
● Access history and read support
Page 6
Domain 3.0: Performance Concepts
3.1 Explain the use of the Query Profile.
● Explain plans
● Data spilling
● Use of the data cache
● Micro-partition pruning
● Query history
3.2 Explain virtual warehouse configurations.
● Multi-clustering
● Warehouse sizing
● Warehouse settings and access
3.3 Outline virtual warehouse performance tools.
● Monitoring warehouse loads
● Query performance
● Scaling up compared to scaling out
● Resource monitors
3.4 Optimize query performance.
● Describe the use of materialized views
● Use of specific SELECT commands
Domain 4.0: Data Loading and Unloading
4.1 Define concepts and best practices that should be considered when loading data.
● Stages and stage types
● File size
● File formats
● Folder structures
● Ad hoc/bulk loading using the Snowflake UI
4.2 Outline different commands used to load data and when they should be used.
● CREATE PIPE
● COPY INTO
● GET
● INSERT/INSERT OVERWRITE
● PUT
● STREAM
Page 7
● TASK
● VALIDATE
4.3 Define concepts and best practices that should be considered when unloading data.
● File formats
● Empty strings and NULL values
● Unloading to a single file
● Unloading relational tables
4.4 Outline the different commands used to unload data and when they should be used.
● LIST
● COPY INTO
● CREATE FILE FORMAT
● CREATE FILE FORMAT … CLONE
● ALTER FILE FORMAT
● DROP FILE FORMAT
● DESCRIBE FILE FORMAT
● SHOW FILE FORMAT
Domain 5.0: Data Transformations
5.1 Explain how to work with standard data.
● Estimating functions
● Sampling
● Supported function types
● User-Defined Functions (UDFs) and stored procedures
5.2 Explain how to work with semi-structured data.
● Supported file formats, data types, and sizes
● VARIANT column
● Flattening the nested structure
5.3 Explain how to work with unstructured data.
● Define and use directory tables
● SQL file functions
● Outline the purpose of User-Defined Functions (UDFs) for data analysis
Page 8
Domain 6.0: Data Protection and Data Sharing
6.1 Outline Continuous Data Protection with Snowflake.
● Time Travel
● Fail-safe
● Data encryption
● Cloning
● Replication
6.2 Outline Snowflake data sharing capabilities.
● Account types
● Snowflake Marketplace and Data Exchange
● Private data exchange
● Access control options
● Shares
Page 9
STUDY AND TRAINING ASSETS FOR EXAM PREPARATION
Effective exam preparation requires more than reading and attending a training course. It
involves using a variety of study and training assets to enhance your understanding of the exam
content. This section will provide you with an overview of the different study and training assets
aligned to each domain covered on the SnowPro Core Certification exam.
First, let’s review some effective strategies for exam preparation:
1) Set a timeline: Schedule your exam and use that date as your target date. Plan
ahead and create a study plan.
2) Understand the exam format and content: When reviewing the exam domain
percentages, pay attention to the weightings in each domain and plan your study
time accordingly. Some domains will have more questions than others.
3) Study with Snowflake assets: Use the exam outline as a checklist. Identify the
objectives and topics you understand and the objectives you feel like you need
more experience with. The next section of this guide will list recommended free
resources for each domain.
4) Review Snowflake Documentation: All Core exam questions are 100%
referenceable with Snowflake Documentation.
5) Practice with sample questions: Gain familiarity with the question formats.
Sample questions can be found at the end of this guide.
Learning is different for everyone! If you learn better with an instructor leading the way,
consider our Snowflake Instructor-Led Training recommendations:
➔ Snowflake Fundamentals Course
➔ SnowPro Core OnDemand Preparation Course
Page 10
RECOMMENDED STUDY RESOURCES
Snowflake Documentation
As the SnowPro Core Certification is Snowflake’s foundational-level certification, the best place
to review Snowflake concepts and features is the Snowflake Documentation. Core exam
questions are tightly aligned to and referenceable from the Snowflake Documentation.
Domain 1.0: Snowflake Data Cloud Features and Architecture Study Resources
Snowflake University On Demand Trainings
Snowflake University, LevelUp: Snowflake’s Key Concepts
Snowflake University, Level Up: Snowflake Ecosystem
Getting Started With Snowflake
Module 2: Prepare your Lab Environment
Module 3: The Snowflake User Interface & Lab Story
Domain 2.0: Account Access and Security Study Resources
Snowflake University On Demand Trainings
Snowflake University, LevelUp: Accounts & Assurances
Snowflake University, Level Up: Container Hierarchy
Getting Started With Snowflake
Module 9: Working with Roles, Account Admin & Account Usage
Video
Snowflake Security Overview (Video)
Reading Asset
Quickly Visualize Snowflake’s Roles, Grants and Privileges (Article)
Domain 3.0: Performance Concepts Study Resources
Snowflake University On Demand Trainings
Snowflake University, Level Up: Query History & Caching
Snowflake University, LevelUp: Query & Result
Snowflake University, LevelUp: Context
Snowflake University: LevelUp: Resource Monitoring
Snowflake University, Essentials - Data Warehousing Workshop
Getting Started With Snowflake
Module 6: Working with Queries, The Results Cache & Cloning
Page 11
Videos
Accelerating BI Queries with Caching in Snowflake (Video)
Snowflake Workloads Explained: Data Warehouse (Video)
Tackling High Concurrency with Multi-Cluster Warehouses (Video)
Reading Assets
Caching in Snowflake Data Warehouse (Article)
How to: Understand Result Caching (Article)
Managing Snowflake’s Compute Resources (Blog)
Performance Impact from Local and Remote Disk Spilling (Article)
Search Optimization: When & How to Use (Article)
Snowflake Materialized Views: A Fast, Zero-Maintenance Accurate Solution (Blog)
Tuning Snowflake (Article)
Using Materialized Views to Solve Multi-Clustering Performance Problems (Article)
Domain 4.0: Data Loading and Unloading Study Resources
Snowflake University On Demand Trainings
Snowflake University, Level Up: Data Loading
Badge 1: Data Warehousing Workshop
Getting Started With Snowflake
Module 4: Preparing to Load Data
Module 5: Loading Data
Videos
Building and Deploying Continuous Data Pipelines (Video)
Easily Loading and Analyzing Semi-Structured Data in Snowflake (Video)
Reading Assets
Best Practices for Data Unloading (Article)
Best Practices for Using Tableau with Snowflake (White Paper, requires email for access)
How to Load Terabytes into Snowflake - Speeds, Feeds and Techniques (Blog)
Domain 5.0: Data Transformations Study Resources
Snowflake University On Demand Training
Badge 2: Data Application Builders Workshop
Getting Started With Snowflake
Module 7: Working with Semi-Structured Data, Views & Joins
Page 12
Video
Easily Loading and Analyzing Semi-Structured Data in Snowflake (Video)
Reading Assets
Best Practices for Managing Unstructured Data (E-book)
Structured vs Unstructured vs Semi-Structured Data (Blog)
Understanding Unstructured Data With Language Models (Blog)
Domain 6.0: Data Protection and Data Sharing Study Resources
Snowflake University On Demand Trainings
Snowflake University, Level Up: Container Hierarchy
Snowflake University, Level Up: Backup and Recovery
Snowflake University, Essentials - Sharing, Marketplace & Exchanges Workshop
Badge 3: Sharing, Marketplace, & Exchanges Workshop
Getting Started With Snowflake
Module 8: Using Time Travel
Module 10: Data Sharing
Videos
Data Protection with Time Travel in Snowflake (Video)
Getting Started on Snowflake with Partner Connect (Video)
Top 10 Cool Snowflake Features, #7: Snowflake Fast Clone (Blog + Video)
Reading Assets
Meta Data Archiving with Snowflake (Article)
Snowflake Continuous Data Protection (White Paper)
Snowflake Product Releases
If you are studying for the SnowPro Core Recertification exam, make sure you are up to date
with what’s new with Snowflake:
Snowflake Documentation: What’s New?
Page 13
SNOWPROⓇ CORE CERTIFICATION SAMPLE QUESTIONS
1. Which type of data integration tools leverage Snowflake's scalable compute for data transformation?
A. Database replication
B. ELT
C. ETL
D. Streaming
2. What is the maximum number of consumer accounts that can be added to a share object?
A. 1
B. 10
C. 100
D. Unlimited
3. What technique does Snowflake use to limit the number of micro-partitions scanned by each query?
A. Pruning
B. Indexing
C. Map Reduce
D. B-Tree
4. Which of the following are options when creating a virtual warehouse? (Select TWO).
A. Auto-suspend
B. Storage size
C. Auto-resume
D. Cache size
E. Default role
5. Which role in Snowflake allows a user to administer users and manage all database objects?
A. SYSADMIN
B. SECURITYADMIN
C. ACCOUNTADMIN
D. ROOT
Page 14
Correct responses for sample questions:
1: B, 2: D, 3: A, 4: A and C, 5: C
Ready to sign up for an exam? Navigate here to get started.
The information provided in this guide is provided for your internal purposes only and may not
be provided to third parties.
IN ADDITION, THIS STUDY GUIDE IS PROVIDED “AS IS”. NEITHER SNOWFLAKE
NOR ITS SUPPLIERS MAKES ANY OTHER WARRANTIES, EXPRESS OR IMPLIED,
STATUTORY OR OTHERWISE, INCLUDING BUT NOT LIMITED TO WARRANTIES OF
MERCHANTABILITY, TITLE, FITNESS FOR A PARTICULAR PURPOSE OR
NONINFRINGEMENT.
Page 15