2-Tier Scalable Web Application on AWS
This project is a 2-tier scalable web application on AWS.
The web tier runs on EC2 instances in public subnets, managed by an Application Load Balancer (ALB) and Auto Scaling Group (ASG).
The database tier uses RDS MySQL in private subnets for secure data storage.
Optional Route 53 DNS maps a domain name to the ALB or EC2 IP for external access.
