# AWS VPC Peering Project

## Project Overview
This project demonstrates secure private communication
between two Amazon Virtual Private Clouds (VPCs) using
AWS VPC Peering.

## Architecture
- VPC A: 10.10.0.0/16
- VPC B: 10.20.0.0/16
- Bastion Host: 10.10.1.10
- App-A: 10.10.2.10
- App-B: 10.20.1.10

## AWS Services Used
- Amazon VPC
- Amazon EC2
- VPC Peering
- Internet Gateway
- Route Tables
- Security Groups

## Implementation
1. Created two VPCs with non-overlapping CIDR blocks.
2. Configured public and private subnets.
3. Created and accepted VPC Peering.
4. Configured forward and return routes.
5. Configured security groups.
6. Established SSH connectivity through a bastion host.
7. Tested private communication using ICMP ping.
8. Performed controlled failure and recovery testing.

## Project Evidence
- Screenshots: `Screenshots/`
- Project Report: `Report/`

## Student Details
- Name: Pratik Pradip Shinde
- College: Bharati Vidyapeeth College of Engineering, Pune
- Batch: To be updated

## Security Note
Private keys and AWS credentials are not included
in this repository.
