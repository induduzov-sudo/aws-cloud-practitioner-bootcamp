# Internet Gateway

## What Is an Internet Gateway?
An Internet Gateway (IGW) is an AWS component that connects a VPC to the internet.

## Why It Is Required
- Without an IGW, resources in public subnets cannot communicate with the internet.  
- Applications would be isolated, blocking user access and outbound traffic.

## How Traffic Flows
1. User request originates from the internet.  
2. Traffic passes through the Internet Gateway.  
3. Routed into the public subnet.  
4. Delivered to the EC2 instance or load balancer.  

## What Happens Without an IGW
- EC2 instances cannot download updates.  
- Users cannot reach web applications.  
- The VPC remains isolated, suitable only for private workloads.