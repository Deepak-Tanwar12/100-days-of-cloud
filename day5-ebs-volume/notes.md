# Day 5 – EBS Volume Creation (AWS Storage)

Today focused on AWS block storage using Elastic Block Store (EBS).

## Key Concepts
- EBS provides persistent block storage for EC2
- Volumes are created in a specific Availability Zone
- Volumes must be attached to EC2 in the same AZ
- gp3 is a general-purpose SSD volume type
- Data persists even if EC2 instance is stopped

## Practical Task
Created an EBS volume with the following configuration:
- Name: xfusion-volume  
- Type: gp3  
- Size: 2 GiB  

## Why This Matters
Block storage is critical for:
- databases  
- application storage  
- backups  
- stateful workloads  
- recovery systems  

Understanding storage fundamentals is essential for real cloud architecture.

## Learning Outcome
- Understood EBS volume types
- Learned AZ-based resource binding
- Understood persistent storage behavior
- Hands-on experience with AWS storage services

## Proof
Screenshots available in the `screenshots/` folder.
