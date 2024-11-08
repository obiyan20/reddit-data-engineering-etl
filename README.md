# reddit-data-engineering-etl

## Introduction
This project extracts data from Reddit APIs to analyze discussions about 'cryptocurrency' and examine the biases in those discussions. The project utilizes Jupyter Notebooks to connect to the APIs and employs Python for performing ETL (Extract, Transform, Load) processes.

### Architecture
![Architecture Diagram](https://github.com/obiyan20/reddit-data-engineering-etl/blob/main/Reddit_etl_project.jpg)


### About dataset Used
Reddit APi contains information about **cryptocurrency** and to examine the biases in those discussions - [Reddit API ](https://www.reddit.com/prefs/apps)

### Services Used
1. **S3 (Simple Storage Service):** Amazon S3 (Simple Storage Service) is highly scalble object storage service that can store and retrieve any amount of data from anywhere on the web. it is commonly used to store and distribute large media files, data backups, and static wesite files.

2. **AWS Lambda:** AWS Lamdda is a serverless computing service that lets you run your code without managing servers. you can use lambda to run code in response to events like changes in S3, DynamoDB, or other AWS

3. **Cloud Watch:** Amazon CloudWatch is a monitoring service for AWS resources and the applications you on them. you can run on them. you can use cloudWatch to collect and track metrics, collect and monitor log file,  and alarms.

4. **Glue Crawler:** is a full managed service that automtically crawls your data source, identifies data formats, and infer schemas to create an AWS Glue Data catalog.

5. **Amazon Athena:**: Amazon Athena is an interactive query service that makes it easy to analze data in Amazon S# usind standard SQL. you can use Athena to analze data in your Glu Data Catalog or in other S3 buckets.

### install Packages
1. pip install pandas
2. pip install praw
3. pip install os
4. pip install json
