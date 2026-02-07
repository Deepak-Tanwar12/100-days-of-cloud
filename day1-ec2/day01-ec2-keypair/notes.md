# Day 1 – EC2 Key Pair Creation

Focused on understanding EC2 authentication and secure access using key pairs.

## Key Concepts
- EC2 instances use key pairs for SSH authentication
- Private key (.pem) is required to access Linux instances
- Public key is stored by AWS
- Key pairs are region-specific
- Losing a private key means losing access to the instance

## Practical Task
Created an EC2 key pair named `devops-kp` using the AWS console.

## Why This Matters
Key pairs are the foundation of secure server access in AWS.
Without proper key management:
- Instances become inaccessible
- Security risks increase
- Recovery becomes complex

## Learning Outcome
- Understood EC2 authentication model
- Learned importance of private key security
- Understood region-level resource isolation
- Learned real-world cloud access control basics

## Proof
Screenshots available in the `screenshots/` folder.
