# AWS-EC2-RDS-Backup-Automation-using-Lambda
## Overview
Automated daily snapshot backups for EC2 and RDS using AWS Lambda and CloudWatch Events.

## Stack
- AWS Lambda
- EC2, RDS, S3
- CloudWatch Events
- Python (Boto3)

## Features
- Daily snapshot backup
- Retention policy to delete old backups
- Logs stored in S3
- Alerts via SNS

## Setup Instructions
1. Create IAM role with backup permissions
2. Deploy Lambda from provided script
3. Set CloudWatch Event rule for daily trigger
4. Monitor logs and alerts

## Outcome
- Zero manual backup efforts
- Cost control with automated cleanup
