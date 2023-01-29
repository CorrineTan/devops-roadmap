# Learning Terrafrom Basics

## Terrafrom Command Basics

1. terraform init 

Purpose: 
- initialize a working directory containing terraform config files.
- download providers.

2. terraform validate

Purpose: 
- ensure the terraform config files are syntactically valid and interanlly consistent.

3. terraform plan

Purpose:
- create execution plan: perform a refresh and determine what action are neccessary to achieve the desired state specified in config files.

4. terraform apply

Purpose:
- apply changes requried to reach the desired state of the configuraiton.

Now the folders have:
- main.tf
- terraform.tfstate
- terraform.lock.hcl (hash)
- terraform/providers/xxx/xxx

5. terraform destroy

Purpose:
- Destroy the Terraform-managed infrastructure.


