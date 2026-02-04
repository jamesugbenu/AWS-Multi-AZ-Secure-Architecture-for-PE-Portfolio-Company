# AWS-Multi-AZ-Secure-Architecture-for-PE-Portfolio-Company
AWS Multi-AZ Secure Architecture for a Private Equity Portfolio Company

# AWS Multi-AZ Secure Architecture for Private Equity Portfolio Company

## Overview
This repository contains a reference architecture designed for a Private Equity portfolio company migrating from on-premises infrastructure to AWS.

The solution focuses on:
- High availability (Multi-AZ)
- Security and compliance
- Cost optimisation (FinOps)
- Infrastructure as Code
- CI/CD automation
- Scalability across portfolio companies

## Architecture Diagram
![Architecture](diagrams/aws-pe-multi-az-architecture.png)

## Key AWS Services
- Amazon VPC (Multi-AZ)
- Application Load Balancer
- Amazon ECS (Fargate)
- Amazon RDS (Multi-AZ)
- Amazon S3
- AWS IAM & KMS
- CloudWatch & CloudTrail

## Infrastructure as Code
Terraform is used to provision and manage infrastructure consistently across environments.

## CI/CD
A GitHub Actions pipeline automates application deployment and infrastructure changes.

## FinOps
Cost visibility and governance are implemented using tagging, budgets, and cost monitoring to align cloud spend with business outcomes.

## Use Case
Designed for Private Equity firms seeking rapid post-acquisition value creation through cloud modernisation.
