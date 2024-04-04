AWS - Project: Build and use a module in terraform

The code in the VPC directory creates a VPC, subnet and ami fetch, and outputs the subnet ID and ami ID.

The code in the working directory calls upon this module, and passes the parameters used in the module to create a VM. The created VM outputs the private ip when finished.  

Run:

Terraform fmt -recursive

Terraform validate

Terraform plan
#Module created will be referenced here

Terraform apply
