
ECS on AWS EC2 using Terraform, follow following steps to configure the underlying infrastructure for a container cluster:

1. Provision your VPC, subnet, routing table and security group.
      Within this file, we'll specify the instructions to:
      1. Create a VPC
      2. Create an Internet Gateway
      3. Create a Public Subnet
      4. Create a Routing Table
      5. Associate the Routing Table to the Public Subnet
      6. Create a Security group for the VPC

2. Set up IAM roles and instance profile.
3. Set up an ALB.
4. Set up an Autoscaling group and launch configuration.
5. Create the ECS cluster.
6. Create the Task definition and service to run on the ECS cluster.
