# AWS Monitoring and Shared Storage Infrastructure Project

## Project Overview

This project involved designing and implementing a centralized monitoring and storage solution for AWS application servers.

## Architecture Diagram

The architecture consists of two application servers running Datadog agents. Logs are forwarded to Datadog for monitoring and analysis. Slack is integrated for alert notifications, while Amazon EFS provides shared storage accessible from multiple application servers.

![Architecture Diagram](aws-monitoring-architecture.png)
## Amazon EFS File System

Created an encrypted Amazon Elastic File System (EFS) to provide scalable shared storage.

![Amazon EFS File System](aws-efs-filesystem.png)

## Amazon EFS Access Point

Configured an EFS Access Point to manage secure application access.
## Security Considerations

- EFS encrypted at rest.
- Principle of least privilege applied to AWS resources.
- Access to EFS controlled through Access Points.
- Monitoring and alerting configured to detect operational issues.
- Linux permissions validated for shared storage access.
![Amazon EFS Access Point](aws-efs-access-point.png)

## Linux EFS Validation

Validated the EFS mount from the Linux application server using SSH.

![Linux EFS Validation](linux-efs-validation.png)

## Technologies Used

- AWS EC2
- Amazon EFS
- Datadog
- Slack
- Linux

## Skills Demonstrated

- Cloud Infrastructure
- AWS Administration
- Monitoring and Observability
- Incident Response
- Log Management
- Technical Troubleshooting
## Key Achievements

- Deployed a centralized monitoring solution using Datadog.
- Configured Amazon EFS for shared storage across multiple EC2 instances.
- Implemented EFS Access Points for secure file system access.
- Integrated monitoring alerts with Slack notifications.
- Validated EFS mounting and file sharing from Linux servers.
- Demonstrated infrastructure monitoring, storage management, and troubleshooting skills.
## Security Considerations

- EFS encrypted at rest.
- Principle of least privilege applied to AWS resources.
- Access to EFS controlled through Access Points.
- Monitoring and alerting configured to detect operational issues.
- Linux permissions validated for shared storage access.
