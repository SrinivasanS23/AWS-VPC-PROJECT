# AWS VPC Project – Public and Private Subnets

## Overview

I implemented an AWS Virtual Private Cloud (VPC) environment with public and private subnets to understand AWS networking, routing, internet connectivity, and network security.

This hands-on project is based on the AWS project tutorial by Abhishek Veeramalla. Through this implementation, I gained practical experience configuring AWS networking components and managing connectivity between cloud resources.

## Project Objectives

- Created a custom AWS VPC to establish an isolated virtual network.
- Configured public and private subnets to organize resources based on their network access requirements.
- Set up an Internet Gateway to provide internet connectivity to public subnet resources.
- Configured a NAT Gateway to enable outbound internet access for resources in the private subnet.
- Created and configured route tables to control network traffic.
- Deployed EC2 instances within the VPC environment.
- Configured Security Groups and Network ACLs to control network access.
- Explored network isolation, traffic flow, and secure cloud infrastructure design.

## AWS Services Used

- **Amazon VPC** – Created and managed the virtual network.
- **Amazon EC2** – Deployed virtual server instances.
- **Public and Private Subnets** – Organized resources based on network accessibility.
- **Internet Gateway** – Enabled internet connectivity for public subnet resources.
- **NAT Gateway** – Configured outbound internet connectivity for private subnet resources.
- **Route Tables** – Managed routing between subnets and network gateways.
- **Security Groups** – Configured instance-level traffic rules.
- **Network ACLs** – Applied subnet-level network traffic controls.
  

## Architecture

I implemented a VPC architecture that separates public and private network resources and uses routing and security controls to manage network traffic.

The architecture demonstrates how public-facing resources can communicate with the internet while private resources remain isolated from direct inbound internet access.

Refer to `architecture.png` for the architecture diagram.

## Project Screenshots

I documented the AWS configuration and implementation using screenshots.

The `Screenshots/` directory contains the available evidence of the project, including:

- VPC configuration
- Public and private subnet configuration
- Route table configuration
- Internet Gateway setup
- NAT Gateway setup
- Security Group configuration
- EC2 instance deployment

## Key Learnings

Through this project, I gained hands-on experience with:

- Creating and configuring an AWS VPC.
- Understanding public and private subnet architecture.
- Configuring route tables and network gateways.
- Understanding the difference between Internet Gateway and NAT Gateway functionality.
- Applying network security controls using Security Groups and Network ACLs.
- Understanding how traffic flows between AWS resources and the internet.
- Learning the fundamentals of AWS network troubleshooting.

## Learning Resource

This project was implemented by following the hands-on AWS project tutorial by Abhishek Veeramalla.

**YouTube Tutorial:**  
https://www.youtube.com/watch?v=FZPTL_kNvXc

## Security and Cost Management

- Avoided storing AWS credentials, private keys, or other sensitive information in the repository.
- Considered AWS resource costs when creating network infrastructure.
- Reviewed and removed resources when they were no longer needed to avoid unnecessary charges.

## Conclusion

This project helped me strengthen my understanding of AWS networking fundamentals and gain practical experience configuring a VPC with public and private subnets, routing, gateways, EC2 instances, and network security controls.

It forms part of my hands-on learning journey in AWS Cloud and DevOps.
