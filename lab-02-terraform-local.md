# Lab 2: Terraform - Local Dev Environment

## Create a LogDNA instance through Terraform
1. Clone https://github.com/ibm-garage-dach/logdna-terraform
2. Update the default value of those variables in `variables.tf`
* ibmcloud_api_key - use the API key you have generated earlier in the UI or use `ibmcloud iam api-key-create 'your initials'-TerraformKey -d "API Key for Terraform" --file terraform_key.json`
* resource_group - use the bootcamp resource group - hint: `ibmcloud iam resource groups`
* unique_id - use "'your initials'-dev", e.g. "gw-dev"


3. Initialize your Terraform environment
4. Create your Terraform execution plan, examine and validate it 
5. Apply your Terraform plan
6. Validate that the LogDNA service has been created - hint: `ibmcloud resource service-instances | grep 'your initials'`
7. Destroy the LogDNA service


## Examine IBM Cloud Terraform Plugin examples
1. Clone https://github.com/IBM-Cloud/terraform-provider-ibm
2. Explore the `/examples` directory
3. Take a look at https://cloud.ibm.com/docs/terraform?topic=terraform-index-of-terraform-resources-and-data-sources
