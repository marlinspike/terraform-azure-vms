#Terraform on Azure#

Terraform is a first class citizen on Azure, and if you're already familiar with it, or looking for a great infra-as-code solution for Azure, Terraform may be just right.

This is an example of how to create multiple VMs in Azure using Terraform. *Note:* This script creates three virtual machines, to demonstrate how you go about setting up n infra elements quickly and easily. This implies consumption and cost.

**Prerequisites**
- An Azure Subscription
- Install Terraform: https://www.terraform.io/downloads.html

**First Steps**
- Configure the Azure Provider: https://www.terraform.io/docs/providers/azurerm/

**Running the example**
- Terraform init
- Terraform plan #This shows you what will happen, without actually performing the deployment
- Terraform apply #This actually applies the deployment to Azure
- Terraform destroy #This takes down everything that this script deployed