# Day 8: AWS EC2 Deep Dive - Instance Types and Auto Scaling

## Topics Covered

### 1. EC2 Instance Types
- **General Purpose (t3, m5)**: Balanced compute, memory, networking
- **Compute Optimized (c5, c6)**: High-performance processors
- **Memory Optimized (r5, x1)**: High memory-to-CPU ratio
- **Storage Optimized (i3, d2)**: High sequential I/O access
- **GPU Instances (p3, g4)**: Graphics processing

### 2. Instance Families
- **T2/T3**: Burstable performance for lightweight workloads
- **M5**: General purpose, balanced for most workloads
- **C5**: Compute-optimized, ideal for batch processing
- **R5**: Memory-optimized for in-memory databases

### 3. Auto Scaling Concepts
- **Launch Templates**: Define EC2 instance configuration
- **Auto Scaling Groups**: Automatic scaling based on demand
- **Scaling Policies**: Target tracking, step scaling, scheduled scaling
- **Load Balancers**: Distribute traffic across instances

### 4. Key Features
- Elastic IP Addresses
- Security Groups and NACLs
- VPC Placement Groups
- Tenancy Options (shared, dedicated, host)

## Hands-on Labs
- [x] Launch EC2 instance with different instance types
- [x] Create Auto Scaling Group
- [x] Configure Load Balancer
- [ ] Implement custom scaling policies

## Resources
- AWS EC2 Documentation: https://docs.aws.amazon.com/ec2/
- Instance Types Guide: https://aws.amazon.com/ec2/instance-types/
- Best Practices: https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-best-practices.html

## Notes
- EC2 is the foundation for most AWS infrastructure
- Understanding instance types is crucial for cost optimization
- Auto Scaling ensures high availability and resilience
- Remember the pricing model: On-demand, Reserved, Spot instances

## Practice Questions
1. When should you use Spot Instances over On-Demand?
2. What is the difference between instance store and EBS volumes?
3. How does Auto Scaling work with Load Balancers?
4. Which instance type is best for database workloads?

## Next Steps
- Study EBS volumes and storage optimization
- Practice creating multi-tier architectures
- Learn about CloudWatch monitoring for EC2
