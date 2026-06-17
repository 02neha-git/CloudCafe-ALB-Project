# Cloud Cafe - AWS Application Load Balancer Project

## Project Overview

This project demonstrates how to deploy two EC2 instances behind an AWS Application Load Balancer (ALB).

## Services Used

- Amazon EC2
- Application Load Balancer
- Target Groups
- Security Groups
- Ubuntu
- Nginx

## Architecture

Users
   |
   V
Application Load Balancer
   |
 -------------------
 |                 |
 V                 V
Server1         Server2

## Implementation Steps

1. Created two Ubuntu EC2 instances.
2. Installed Nginx on both servers.
3. Configured custom index.html pages.
4. Created a Target Group.
5. Registered both EC2 instances.
6. Created an Application Load Balancer.
7. Configured Health Checks.
8. Tested traffic distribution.
9. Simulated server failure.
10. Verified automatic failover.

## Learning Outcome

- Load Balancing
- Health Checks
- High Availability
- AWS Networking
- Nginx Configuration

## Author

Neha Patil
