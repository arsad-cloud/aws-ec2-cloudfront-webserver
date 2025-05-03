# AWS Cloud-Based Web Server Development

This project demonstrates how to deploy and secure a web application on AWS using key cloud services.

## Key Features
- **EC2 Web Server (Windows):** Hosted a static website using IIS on Windows EC2.
- **CloudFront CDN:** Integrated CloudFront for global low-latency access and high availability.
- **Security:** IAM roles, security groups, and CloudTrail for access control and monitoring.

## Technologies Used
- Amazon EC2 (Windows Server)
- Amazon CloudFront
- IAM Roles & Security Groups
- AWS CloudTrail

## Architecture
User --> CloudFront --> EC2 (Windows Server + IIS)
