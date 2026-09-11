### Basic Terraform Commands
alias tf=terraforn (use alias tf instate of terraform)
##  Initializes a local Terraform working directory.
terraform init

##  Generates and displays an execution plan
terraform plan

##  Executes the actions proposed in the plan phase.
terraform apply

##  Deletes all remote infrastructure managed by the configuration file.
terraform destroy

## Checks whether a configuration is syntactically valid and internally
terraform validate

## Lists every resource itemized within the state file
terraform state list

##  Automatically rewrites Terraform configuration files into a canonical layout and style
terraform fmt