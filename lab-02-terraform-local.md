# Lab 2: Terraform - Local Dev Environment

1. Clone https://github.com/ibm-garage-dach/logdna-terraform
2. Update the default value of those variables in `variables.tf`
* ibmcloud_api_key - use the API key you have generated earlier in the UI or use `ibmcloud iam api-key-create <your initials>-TerraformKey -d "API Key for Terraform" --file terraform_key.json`
* resource_group - use the bootcamp resource group - hint: `ibmcloud iam resource groups`
* unique_id - use "'your initials'-dev", e.g. "gw-dev"


3. Initialize your Terraform environment
4. Create your Terraform Provisioning plan
5. Apply your Terraform plan
