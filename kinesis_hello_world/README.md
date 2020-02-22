# Simple use case with Kinesis

Simple use case:
- Push data to Kinesis Data Stream
- Save data using Kinesis Firehose to S3 bucket with basic configuration

## Architecture

![](./architecture.png)

## Run

### Create CloudFormation Stack

Create resources using CloudFormation template: [template.yml](template.yml).

### Generatate test data to Kinesis source stream

Generate sample data to Kinesis using Kinesis Data Generator (KDG) tool: https://awslabs.github.io/amazon-kinesis-data-generator/web/producer.html

#### Configure account

Create an Amazon Cognito User, follow instruction from Kinesis Data Generator (KDG): https://awslabs.github.io/amazon-kinesis-data-generator/web/help.html

### Start data generation

Access the Kinesis Data Generator (KDG) following instruction: https://awslabs.github.io/amazon-kinesis-data-generator/web/help.html
