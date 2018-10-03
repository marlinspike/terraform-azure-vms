This is an example of how to create multiple VMs in Azure using Terraform.

Prerequisites:
- An Azure Subscription
- Install Terraform: https://www.terraform.io/downloads.html

First Steps:
- Configure the Azure Provider: https://www.terraform.io/docs/providers/azurerm/

Running the example:
- Terraform init
- Terraform plan #This shows you what will happen, without actually performing the deployment
- Terraform apply #This actually applies the deployment to Azure
- Terraform destroy #This takes down everything that this script deployed
