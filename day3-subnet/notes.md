# Day 3 – Subnet Creation (AWS VPC)

Today focused on creating a subnet inside the default VPC and understanding basic VPC networking structure.

## Key Concepts
- VPC is a logically isolated network in AWS
- Subnets divide a VPC into smaller networks
- Subnets are bound to a single Availability Zone
- CIDR blocks define IP address ranges
- Subnet CIDR must be inside VPC CIDR and must not overlap

## Practical Task
Created a subnet named `devops-subnet` inside the default VPC.

### Configuration:
- VPC CIDR: 172.31.0.0/16  
- Subnet name: devops-subnet  
- Subnet CIDR: 172.31.100.0/24  
- Availability Zone: us-east-1a  

## Why This Matters
Subnets are the foundation of cloud networking.
They control:
- network segmentation  
- security boundaries  
- traffic flow  
- architecture design  
- scalability planning  

## Learning Outcome
- Understood VPC vs Subnet relationship
- Learned CIDR range planning
- Learned subnet isolation per AZ
- Understood non-overlapping CIDR logic
- Hands-on experience with AWS networking

## Proof
Screenshots available in the `screenshots/` folder.
