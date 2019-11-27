# Jumpbox-setup-on-AWS-Cloud
Jumpbox setup on AWS Cloud

**Objective**: Build and setup a Jumpbox (public EC2 instance) to access a private EC2 instance located in a private subnet with no direct access to Internet.

##Environment requirements:
1 VPC
2 subnets (1 **public** and 1 **private**) in one Availability Zone
1 **Internet Gateway** associated with the public subnet
3 Amazon EC2 instances (**Jumpbox, NAT, FI (Final Instance**)
2 Elastic IP (EIPs) (one for each instance in the public subnet)
2 Route tables (one for each subnet)
3 Security groups (one for each instance)

