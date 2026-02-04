# Day 7 – EC2 Instance Type Change (Optimization)

Today focused on optimizing cloud resources by resizing an EC2 instance based on utilization.

## Key Concepts
- EC2 instance types define compute capacity
- Underutilized instances increase unnecessary cost
- Instance type changes require stopping the instance
- Status checks must pass before and after changes
- Optimization is a core responsibility in real cloud environments

## Practical Task
Modified an EC2 instance by changing its instance type:
- Instance name: nautilus-ec2
- Changed from: t2.micro
- Changed to: t2.nano

The instance was safely stopped, resized, and started again.

## Why This Matters
Cloud is pay-as-you-go.
Choosing the right instance size:
- reduces cost
- improves efficiency
- avoids wasted resources
- supports scalable design

Optimization is just as important as deployment.

## Learning Outcome
- Learned how to safely resize EC2 instances
- Understood downtime considerations
- Practiced cost-aware cloud management
- Gained hands-on experience with EC2 optimization workflows

## Proof
Screenshots available in the `screenshots/` folder.
