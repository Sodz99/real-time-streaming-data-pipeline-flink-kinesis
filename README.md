# Build a real-time Streaming Data Pipeline using Flink and Kinesis

Build a real-time Streaming Data Pipeline using Flink and Kinesis — AWS Data Engineering project.

## Overview
Perishable data is information whose value can significantly decline over a period of time. When the operating conditions change to the point that the knowledge is no longer helpful, the information loses a large amount of its value. This information is frequently produced in an IoT computing context. Managing perishable data provides a number of benefits. Real-time data provides you with the information you need almost instantly and in the context which helps make smarter business decisions. The use of data from edge computing devices speeds up reaction time and minimizes time to action. Such data does not need to be kept in data centers for a long time and maybe deleted after usage, saving storage space and money. Systems are usually designed on constant patterns and can’t scale with peaks in the load resulting in latency and server failures. This Project will simulate real-time accidents data and architect a pipeline that will help us analyze and take quick actions using AWS Kinesis

## Data
This Project uses the US car accidents dataset which includes a few of the following fields:
- Severity
- Start_Time
- End_Time
- Location
- Description
- City
- State

_Data is not included in this repository._

## Tech stack
➔Languages- SQL, Python3 ➔Services - AWS S3, AWS Glue, AWS Athena, AWS Cloud9, Apache Flink, Amazon Kinesis, Amazon SNS, AWS Lambda, Amazon CloudWatch, Grafana, Apache Zepplin ➔Tool: Terraform

Amazon S3 Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security, and performance. Users may save and retrieve any quantity of data using Amazon S3 at any time and from any location.

## How to run

## Project structure
```
.gitignore
Code/
  Code/
    video10 - stream-data-app-simulation.py
    video18 - lambda_function.py
    video23 - lambda_function.py
  Terraform/
    Instructions.md
README.md
```

## Credits
Based on a ProjectPro guided project.
