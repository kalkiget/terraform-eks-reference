
Terraform implementation for provisioning an AWS EKS cluster
using reusable modules and production-safe defaults.

## What this repo demonstrates
- VPC with public/private subnets and NAT
- Managed EKS cluster
- Managed node groups
- Clean separation of variables and outputs
### Usage
```bash
cp terraform.tfvars.example terraform.tfvars
terraform init
terraform apply
