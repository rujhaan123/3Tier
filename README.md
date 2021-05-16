**#Challenge 1**

This is a three tier Azure infra setup using Terraform  namely web, app and DB. 

**Description**
1. The infra has been setup using different terraform modules.
2. resource.tf module has been used for creation of resource group in which we are going to setup our infra
3. vars.tf for defining all the variables
4. terraform.tfvars declares all the values of those variables
5. main.tf contains set of configuration for modules
6. network.tf defines the virtual network and subnets for all tiers of VM's
7. compute.tf defines all the resources required for infra set
8. security.tf for setting up of security such as creation of nsg and allowing/blocking inbound/outbound traffic

**Deployment**
1. terraform init-to initialize working directory.
2. terraform plan: used to create execution plan.
3. terraform validate: validates the configuration files in a directory.
4. terraform apply: used to apply changes.
