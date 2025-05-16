This project defines the production-level network architecture for the Ventura Application, featuring a well-structured VPC (10.0.0.0/16) segmented into public and private subnets across multiple Availability Zones (us-west-1a and us-west-1c). It includes:

NAT/ALB Subnets for internet-facing resources.

Web Layer Subnets for proxy and web servers.

Application Layer Subnets for backend services.

Database Subnets for RDS (MySQL) with high availability.

Each subnet is assigned appropriate CIDR ranges to ensure scalability and security, summing up to 2,072 IPs across the environment.
