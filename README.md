# Project 2 - Host a Static Website on Amazon S3 Using Terraform

## Objective
Deploy a simple static website on Amazon S3 using Terraform.

## Files
- main.tf
- variables.tf
- outputs.tf
- index.html

## Commands used

terraform init

terraform validate

terraform plan -var="bucket_name=my-unique-bucket"

terraform apply -var="bucket_name=my-unique-bucket"
