# aws-retail-pipeline
End to end AWS data pipeline — S3 Lambda SQS Glue Redshift SNS

# AWS Retail Data Pipeline
 
End to end automated data pipeline built on AWS.
When a CSV file is uploaded to S3 the entire pipeline
runs automatically — Lambda detects it, SQS queues it,
Glue cleans and transforms it, Redshift loads it,
and SNS sends email notifications.
 
## Architecture
