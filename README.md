# AWS Hands-On Labs

A collection of practical AWS labs completed while learning how to
configure, connect, and troubleshoot cloud services.

These labs cover network isolation, application hosting, availability,
data recovery, and event-driven automation. Each lab documents its
objective, architecture, implementation, and verification.

## Labs

| Lab | Focus | AWS services |
|---|---|---|
| VPC Networking | Public and private subnets, routing, and outbound internet access | VPC, EC2, Internet Gateway, NAT Gateway |
| EC2 Essentials | Instance initialization, metadata, and static public addressing | EC2, Elastic IP |
| Backup and Recovery | Backing up EC2 files and recovering S3 object versions | EC2, S3, IAM |
| Flask Application Hosting | Serving a Python application using Gunicorn and Nginx | EC2 |
| Load Balancing and Auto Scaling | Traffic distribution, failover, and CPU-based scaling | ALB, EC2 Auto Scaling, CloudWatch |
| Lambda and DynamoDB | Writing and retrieving records using Python | Lambda, DynamoDB, IAM |
| Scheduled EC2 Automation | Starting and stopping only tagged instances | EventBridge Scheduler, Lambda, EC2, IAM |
| S3 Email Notifications | Sending upload notifications and file attachments | S3, Lambda, SNS, SES, IAM |

Detailed lab documentation is maintained in the [docs](./docs/) directory.

## What Each Lab Includes

- A practical objective and expected outcome
- An architecture diagram or service workflow
- Configuration and implementation steps
- Code, commands, and IAM policy examples where applicable
- Testing steps and selected screenshots
- Troubleshooting notes and lessons learned
- Resource cleanup instructions

## Skills Practiced

- Configuring VPC networking and routing
- Hosting applications on Linux-based EC2 instances
- Testing load balancing and automatic scaling
- Backing up and recovering data
- Writing AWS automation with Python and Boto3
- Configuring IAM roles and service permissions
- Connecting AWS services through schedules and events

## About This Repository

These are learning labs implemented and tested in an AWS practice
environment. The documentation records the configurations used,
observed results, and issues resolved during implementation.
