AWS

The code in the VPC directory creates a VPC and Subnet, and outputs the subnet ID and ami ID.

The code in the working directory calls upon these ID's and passes them to the parameters used to create a VM. The created VM outputs the private ip when finished.  

Run:

Terraform fmt -recursive

Terraform validate

Terraform plan
#Module created will be referenced here

Terraform apply
