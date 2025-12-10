# AWS-Terraform
Terraform is an Infrastructure-as-Code tool that lets you define and manage AWS resources using configuration files instead of the AWS console. With Terraform, you can create, update, and delete AWS services—such as EC2 instances, VPCs, IAM roles, S3 buckets, and more—using automated, repeatable scripts.
 

## Project Overview
Learning how  to provision my AWS resources and infrastructure within AWS cloud using HACL hashicorp language 'terraform' (Infrastructure as code) 
To be able to do this I shall need a way for terraform to be able monitor my terraform workload using terraform state file
## To carry this out I shall be using terraform commands
 terraform init
 terraform fmt
 terrform validate
 terraform plan 
 terraform apply --auto-approve
 terraform destroy --auto-approve

 # I am trying to create a AWS service mainly a VPC, Public Subnet, Internet Gateway, Route-Table,and a Route-Table association.
Inside the public subnet i am trying to dump a EC2 instance and i'm trying to add all its components such as:
AMI ID, Instance type, SubnetID, Security Group, User data.
 
# Terraform Infrasructure as code this is is the result after I ran terraform apply

<img width="1480" height="727" alt="Image" src="https://github.com/user-attachments/assets/f7b0c77b-fc27-4dc0-924d-b0d5143c3215" />

<img width="1914" height="871" alt="Image" src="https://github.com/user-attachments/assets/d2b1ccd7-a5aa-403e-8095-0c3a4e465287" />