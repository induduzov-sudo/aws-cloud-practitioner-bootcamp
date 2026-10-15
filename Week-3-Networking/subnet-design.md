# Public vs Private Subnets

## Public Subnet
A public subnet is a segment of a VPC with a route to the Internet Gateway.  
- *Internet access*: Directly accessible from the internet.  
- *Examples*: Web servers, load balancers, bastion hosts.  
- *Purpose*: Host applications that must be publicly reachable.

## Private Subnet
A private subnet has no direct route to the Internet Gateway.  
- *Internet access*: Blocked from direct external traffic.  
- *Examples*: Databases, internal systems, backend services.  
- *Purpose*: Protect sensitive workloads from exposure.

## Comparison Table

| Feature            | Public Subnet                  | Private Subnet                  |
|--------------------|--------------------------------|---------------------------------|
| Internet access    | Yes, via Internet Gateway      | No direct access                |
| Typical resources  | Web apps, Load balancers       | Databases, Internal systems     |
| Exposure           | Higher, external traffic flows | More secure, internal only      |
| Security posture   | Must be hardened               | Naturally protected             |

## Security Insight
Sensitive systems should always remain private. Public subnets should only host endpoints that require internet access.
