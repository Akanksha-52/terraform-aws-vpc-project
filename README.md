# terraform-aws-vpc-project
Automated AWS VPC infrastructure provisioning using Terraform (Infrastructure as Code).

# VPC Creation Using Terraform

## Project Overview

This project demonstrates automated AWS infrastructure
creation using Terraform (Infrastructure as Code).

Instead of manually creating AWS resources through
the AWS Management Console, Terraform is used to
provision infrastructure through configuration files.

## AWS Resources Created

- Amazon VPC
- Public Subnet
- Internet Gateway
- Route Table
- Route Table Association
- Security Group
- Amazon EC2 Instance

## Technologies Used

- AWS
- Terraform
- AWS CLI
- Linux
- Visual Studio Code

## Project Architecture

The project creates a custom VPC with a public subnet.
An Internet Gateway provides internet connectivity
through a public route table.

An EC2 instance is launched inside the public subnet.
A security group controls HTTP and optional SSH access.

## Project Structure

terraform-aws-vpc-project/

├── main.tf
├── provider.tf
├── variables.tf
├── outputs.tf
├── .gitignore
└── README.md

## Deployment Steps

### 1. Configure AWS CLI

aws configure

### 2. Verify AWS Account

aws sts get-caller-identity

### 3. Initialize Terraform

terraform init

### 4. Validate Configuration

terraform validate

### 5. Review Infrastructure Plan

terraform plan

### 6. Create AWS Infrastructure

terraform apply

### 7. Access Website

Open the EC2 public IP in your browser
using the HTTP URL displayed in Terraform outputs.

### 8. Destroy Infrastructure

terraform destroy

## Project Outcome

Successfully automated the creation of AWS
networking resources and an EC2 instance using
Terraform.

This project demonstrates practical knowledge of
Infrastructure as Code and AWS networking.

## Author

Akanksha Pathak
