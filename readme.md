Run terraform init command to download the provider code.

Run terraform plan command to see what Terraform will do before actually making any changes.
The plan command is useful for during code reviews
The output of the plan command: anything with a plus sign (+) will be created, anything with a minus sign (-) will be deleted, anything with a tilde sign (~) will be modified.

Run terraform apply to see the difference between what is currently deployes and what the Terraform code has.

The security group allows incoming TCP requests on port 8080 from any IP.