# AWS Hands-On Labs

This repository contains my hands-on AWS lab documentation and practical work.

Each lab includes the steps I followed, AWS Console screenshots, configurations, and observations.

---

## 📚 AWS Labs

| Lab | Topic | AWS Service / Concept |
|---|---|---|
| 01 | EC2 Instance | Amazon EC2 |
| 02 | Creating an Image | AMI / EC2 |
| 03 | Changing the Instance Type | Amazon EC2 |
| 04 | Elastic IP | Elastic IP / EC2 |
| 05 | Volume | Amazon EBS |
| 06 | Snapshot | Amazon EBS |
| 07 | Security Groups | EC2 / Security |
| 08 | Network ACL | Amazon VPC |
| 09 | VPC Networking | Amazon VPC |
| 10 | Gateway | Amazon VPC |
| 11 | S3 Bucket | Amazon S3 |
| 12 | S3 File System | Amazon S3 |
| 13 | Network Load Balancer | Elastic Load Balancing |
| 14 | Route 53 | Amazon Route 53 |
| 15 | RDS | Amazon RDS |
| 16 | Route 53 | Amazon Route 53 |
| 17 | VPC Peering | Amazon VPC |
| 18 | RDS MySQL Hands-on | Amazon RDS / MySQL |
| 19 | CloudWatch EC2 Monitoring | Amazon CloudWatch / EC2 / SNS |

---

## 🛠️ AWS Skills Practiced

- EC2 instance creation and management
- Amazon Machine Images (AMI)
- EC2 instance types
- Elastic IP
- EBS volumes and snapshots
- Security Groups
- Network ACLs
- VPC networking
- Gateways
- Amazon S3
- Network Load Balancer
- Route 53
- VPC Peering
- RDS MySQL
- CloudWatch monitoring
- CloudWatch alarms
- SNS notifications

---

## 📊 CloudWatch Monitoring Lab

The CloudWatch lab demonstrates an EC2 monitoring workflow:

```text
EC2 Instance
     ↓
CPUUtilization Metric
     ↓
CloudWatch
     ↓
CloudWatch Alarm
     ↓
CPU > 80%
     ↓
SNS
     ↓
Email Notification
