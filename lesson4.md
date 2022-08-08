#### Protecting Data inTransit and At- rest

##### Encryption at rest

- Glacier
- Storage Gateway, 
- Snowball
- Fsx for lustre
- Secrets Manager,
- Cloudtrail
- Dynamodb
- Elasticsearch


##### Optional
- EBS
- EFS
- S3
- RDS
- Redshift
- Elasticache 
- DocumentDB
- Neptune
- SQS
- SNS (when there is a retry, you must save the message somewhere)
- Kinesis

##### Implementing Compliance

    AWS CONFIG: Create stream resource changes.
    Apply static logic using AWS-Managed rules

    SSM Inventory: Track EC2 and on-premises
    Security Hub: Consolodiate security contols

