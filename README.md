# Highly Available Multi-Region WordPress Infrastructure on AWS

## Overview
Designed and deployed a multi-region WordPress infrastructure on AWS with production and disaster recovery (DR) environments to ensure high availability and fault tolerance.

## AWS Services Used
- EC2
- Application Load Balancer (ALB)
- Amazon RDS
- Route 53
- AWS Certificate Manager (ACM)
- CloudWatch
- Amazon SNS
- IAM
- VPC

## Features
- Multi-region Production and DR setup
- Route 53 DNS failover routing
- HTTPS using ACM
- ALB for traffic distribution
- CloudWatch monitoring and SNS alerts
- Separate Production and DR databases

## Monitoring
Configured CloudWatch alarms for:
- EC2 CPU Utilization
- RDS metrics
- Target Response Time
- Unhealthy Host Count

Integrated Amazon SNS for real-time alert notifications.

## Architecture
- Production EC2 + ALB + RDS
- DR EC2 + DR ALB + DR RDS
- Route 53 Failover Routing
- ACM SSL/TLS Encryption

## Outcome
Built a highly available and disaster recovery-enabled AWS architecture with monitoring, failover routing, and secure application access.
