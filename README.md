# Ad-Tech Data Engineering and Data Science Portfolio
A data pipeline and analysis project showcasing skills in data engineering and data science, using multiple programming languages and AWS services to process and analyze the Criteo Display Advertising Challenge Dataset.

## Dataset Description
**Dataset:** [Kaggle Criteo Display Advertising Challenge Dataset](https://www.kaggle.com/c/criteo-display-ad-challenge)

This dataset contains 45 million rows of ad click data, with features including anonymized categorical variables, and numerical variables.
The goal is to predict the likelihood of a user clicking on an ad.

## Features
- **Label:** 0 or 1 indicating whether the ad was clicked (1) or not (0).
- **I1-I13:** 13 Integer features representing various user and ad attributes.
- **C1-C26:** 26 Categorical features representing various user and ad attributes.

## Project Goals
1. **Data Ingestion:** Load the raw dataset into an AWS S3 Bucket.
2. **Data Processing:** Clean and transform the data using Apache Spark.
3. **Data Storage:** Store the cleaned data in an AWS RDS PostgreSQL database.
4. **Real-Time Data Ingestion:** Set up a Kafka stream to ingest real-time ad click data into a DynamoDB table.
5. **Data Analysis:** Perform exploratory data analysis (EDA) to identify patterns and insights.
6. **Machine Learning:** Build a machine learning model to predict ad clicks.
7. **Visualization:** Create an interactive visualization to present insights from the data.
8. **Deployment and Monitoring:** Deploy the ETL pipeline on AWS EMR and set up monitoring using AWS Cloud Watch.
9. **Infrastructure as Code:** Use Terraform to manage all AWS infrastructure.

## Tech Stack
**Languages:** SQL, Python, Java, Scala, R, Go, Bash
**Tools/Frameworks:** Apache Spark, Apache Airflow, Hadoop, Kafka, Pandas, AWS Services (S3, RDS, Redshift, EMR, Lamda)
**Database:** PostgreSQL, DynamoDB
**Visualization:** Jupyter Notebooks, Tableau/PowerBI
**IaC (*I*nfrastructure *a*s *C*ode):** Terraform

# User Stories

## Data Ingestion and Storage
1. **US01:** *As a data enigneer, I want to download the Criteo Display Advertising Challenge dataset and store it in an AWS S3 bucket for raw data storage.*
2. **US02:** *As a data engineer, I want to create an ETL pipeline using Apache Spark to process the raw data from S3 and store the cleaned data in an AWS RDS PostgreSQL database.*
3. **US03:** *As a data engineer, I want to set up a Kafka stream to ingest real-time ad click data into a DynamoDB table.*

## Data Processing and Transformation
4. **US04:** *As a data engineer, I want to use Apache Spark and Scala to perform data transformations and aggregations on the cleaned data stored in the PostgreSQL database.*
5. **US05:** *As a data engineer, I want to write Python scripts to automate the ETL process and schedule them using Apache Airflow.*
6. **US06:** *As a data engineer, I want to write SQL queries to extract specific data subsets from the PostgreSQL database for further analysis.*

## Data Analysis and Machine Learning
7. **US07:** *As a data scientist, I want to use Python and Pandas to perform exploratory data analysis (EDA) on the cleaned data to identify patterns and insights.*
8. **US08:** *As a data scientist, I want to build a machine learning model in Python using Scikit-Learn to predict ad clicks based on historical data.*
9. **US09:** *As a data scientist, I want to use R to create detailed visualizations and statistical analyses of the ad click data.*

## Data Visualization
10. **US10:** *As a data scientist, I want to create interactive visualizations using Tableau/PowerBI to present the insights from the ad click data.*
11. **US11:** *As a data scientist, I want to build a Jupyter Notebook with Python and R to document the data analysis process and results.*

## AWS and Distributed Systems
12. **US12:** *As an MLOps engineer, I want to use Terraform to provision and manage all the required AWS infrastructure, including S3, RDS, EMR, Lambda, DynamoDB, and CloudWatch.*
13. **US13:** *As an MLOps engineer, I want to version control my Terraform configuration using Git to maintain infrastructure consistency, and enable collaboration.*
14. **US14:** *As an MLOps engineer, I want to set up monitoring and logging for the data pipeline using AWS CloudWatch.*

## Documentation and Presentation
15. **US15:** *As a project manager, I want to create comprehensive documentation for the entire project, including setup instructions, code explanations, and user guides.*
16. **US18:** *As a project manager, I want to prepare a presentation summarizing the project, highlighting key features, technologies used, and results obtained.*


