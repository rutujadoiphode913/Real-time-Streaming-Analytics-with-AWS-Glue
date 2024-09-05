# Real-time-Streaming-Analytics-with-AWS-Glue
Built a real-time data lake using AWS Glue for ETL and Apache Iceberg for large dataset management on Amazon S3. Ingests streaming data from Amazon Kinesis and enables querying via Amazon Athena. Automated infrastructure setup with AWS CDK in Python for scalable, efficient data processing and analytics.
Technologies Used:

AWS Glue: Serverless ETL service for data transformation.
Apache Iceberg: Open table format for large analytic datasets, enabling in-place updates.
Amazon Kinesis: Real-time data streaming service.
Amazon S3: Scalable object storage for the Iceberg data lake.
Amazon Athena: SQL querying tool for data stored in S3.
AWS CDK (Cloud Development Kit): Infrastructure as code using Python for automated resource provisioning.
Python: Used for developing the AWS CDK and managing Glue job scripts.
Key Features:

Ingests real-time streaming data from Kinesis and processes it with AWS Glue.
Stores transformed data in Iceberg tables on Amazon S3.
Allows efficient querying of data using Amazon Athena.
Deploys infrastructure and resources using AWS CDK, ensuring automated setup.
Handles schema evolution and large-scale data processing with Iceberg.
This project is ideal for learning how to manage real-time data streams and build scalable data lakes using cloud technologies.
