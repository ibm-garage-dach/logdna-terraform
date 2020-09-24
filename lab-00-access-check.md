
# Lab 0: Environment check

Before we can start with any labs, lets validate the environment setup. You should have already setup ibmcloud cli + terraform, but lets make sure
everything is as expected.

Pre-Work
* Install IBM Cloud CLI - - https://cloud.ibm.com/docs/cli - required for infrastructure automation work
* Installation of Terraform and IBM Cloud Provider Plugin - https://cloud.ibm.com/docs/terraform?topic=terraform-getting-started (only "Installing the Terraform CLI and the IBM Cloud Provider plug-in")
* Creation of IBM Cloud API Key - https://cloud.ibm.com/docs/account?topic=account-userapikey#create_user_key

This should work
* `ibmcloud login -sso`
* `terraform version` (should be latest 0.12.x as in the instructions)
