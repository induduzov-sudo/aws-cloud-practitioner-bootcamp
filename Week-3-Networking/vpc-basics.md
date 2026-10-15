# Amazon VPC Basics

## What Is Amazon VPC?
- *Definition*: Amazon VPC (Virtual Private Cloud) is a logically isolated section of the AWS cloud.  
- *Purpose*: It allows you to define your own IP ranges, subnets, routing, and gateways.  
- *Why AWS uses VPCs*: To give customers secure, isolated environments with full control over networking.

## Why VPC Matters
- *Isolation*: Each VPC is separated from others, preventing cross‑traffic.  
- *Security*: Security groups and NACLs protect workloads.  
- *Architecture control*: You design subnets, gateways, and routing to fit business needs.

## Real‑World Example
A bank can deploy:  
- Web servers in public subnets for customer access.  
- Databases in private subnets for sensitive data.  
- Internal applications accessible only within the corporate network.  
This ensures strict security while maintaining usability.
