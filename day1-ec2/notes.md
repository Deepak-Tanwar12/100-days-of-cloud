# Day 2 – AWS Security Groups

Today focused on understanding and configuring AWS Security Groups as network-level firewalls for EC2 instances.

## Key Concepts
- Security Groups act as virtual firewalls
- They control inbound and outbound traffic
- Rules are stateful (return traffic is automatically allowed)
- Attached at instance or network interface level
- Works at instance level, not subnet level

## Practical Task
Created a security group named `datacenter-sg` in the default VPC with the following rules:

### Inbound Rules
- HTTP → Port 80 → Source: 0.0.0.0/0  
- SSH → Port 22 → Source: 0.0.0.0/0  

### Outbound Rules
- Default: All traffic allowed

## Why This Matters
Security groups define the first layer of access control in cloud infrastructure.
Correct configuration is critical for:
- Application availability
- Server security
- Network isolation
- Cloud architecture design

## Learning Outcome
- Understood CIDR ranges
- Learned difference between inbound vs outbound rules
- Learned how AWS controls network traffic at instance level
- Hands-on experience with real AWS console configuration

## Proof
Screenshots added in the `screenshots/` folder.
