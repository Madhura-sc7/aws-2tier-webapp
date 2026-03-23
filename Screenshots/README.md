# Architecture Flow
User → VPC → Subnets (Private/Public) → EC2 → RDS → Docker → ALB → Auto Scaling → ASG Instances

This setup provisions a VPC with subnets, attaches IAM roles, creates EC2 and RDS, runs Docker, and configures ALB with health checks. Finally, auto scaling ensures high availability with ASG instances.
