# Overview

A collection of some Cloudformation templates.

`templates/vpc_lb` - architecture diagram and templates to launch a new VPC with a 4-instance ASG with a load balancer (ALB or CLB) and a bastion instance.

`templates/vpc_eks` - template to launch a new VPC and a new EKS cluster in it.

VPC uses 2 Availability Zones, with 2 subnets per AZ.
