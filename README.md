# AWS VPC Peering Project

## Project Overview
This project demonstrates how to configure AWS networking using Virtual Private Clouds (VPCs), public and private subnets, EC2 instances, security groups, route tables, and VPC peering.

## Objectives
- Create and configure two VPCs.
- Set up public and private subnets.
- Configure an Internet Gateway and route tables.
- Launch EC2 instances in public and private subnets.
- Configure security groups for controlled access.
- Establish VPC peering between two VPCs.
- Test private connectivity using SSH and ICMP ping.

## AWS Services Used
- Amazon VPC
- Amazon EC2
- VPC Peering
- Internet Gateway
- Route Tables
- Security Groups

## Network Configuration

**VPC 1**
- CIDR: `28.0.0.0/16`
- Public subnet: `28.0.1.0/24`
- Private subnet: `28.0.2.0/24`

**VPC 2**
- CIDR: `28.200.0.0/16`
- Private subnet: `28.200.1.0/24`

## Project Report
The PDF report contains the project steps, AWS console screenshots, configuration details, and connectivity test results.

**Report:** `AWS_VPC_Peering_Project_Report.pdf`

## Key Learning Outcomes
- Understanding VPC and subnet configuration.
- Managing network routes and security group rules.
- Accessing a private EC2 instance through a public jump host.
- Establishing private connectivity between peered VPCs.
- Verifying connectivity between instances using ping.

## Author
AWS VPC Peering Project — EWB Internship
