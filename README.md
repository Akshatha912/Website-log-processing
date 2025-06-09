Real-Time Data Pipeline for Website Visitor Logs Using AWS

Project Goal: Build a real-time data pipeline that ingests, processes, and stores website visitor logs using AWS services.

AWS services used:
Service	                                         Purpose
Amazon Kinesis Data Streams	                     Ingest streaming log data
AWS Lambda	                                     Process data in real-time
Amazon S3	                                       Store raw and processed data
AWS Glue Data Catalog	                           Organize metadata for Athena
Amazon Athena	                                   Query the processed logs
IAM	                                             Manage permissions

Scenario:
Simulate website traffic logs using a Python script that sends data to a Kinesis Data Stream. Lambda processes the stream and stores the data into an S3 bucket. Query the data using Athena.
