# Day 10 – Elastic IP Association

Today focused on networking in AWS by attaching an Elastic IP to an EC2 instance.

## Key Concepts
- Elastic IP is a static public IPv4 address
- Helps maintain a fixed address for services
- Useful for DNS mapping, APIs, and production workloads
- Elastic IP remains the same even if instance is stopped and started

## Practical Task
Attached an Elastic IP to an EC2 instance:
- Instance name: devops-ec2
- Elastic IP: devops-ec2-eip
- Region: us-east-1

## Why This Matters
In real cloud environments:
- Public IPs change on restart
- Elastic IP ensures stable connectivity
- Important for production systems and external integrations

## Learning Outcome
- Learned how to associate an Elastic IP
- Understood static vs dynamic IP addresses
- Gained hands-on experience with AWS networking

## Proof
Screenshots available in the `screenshots/` folder.
