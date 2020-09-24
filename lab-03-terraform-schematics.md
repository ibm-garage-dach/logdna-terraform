# Lab 3: Terraform - IBM Schematics

1. Create a workspace in Frankfurt in the bootcamp resource group named 'your initials'-dev-workspace
2. Import your terraform template by pointing to https://github.com/ibm-garage-dach/logdna-terraform, choose Terraform v0.12. Hint: if you leverage private repos your git access token needs to have read repo + api permissions - not needed here, as its a public repo.
3. Change the variables as you have done before - api key, resource group and unique key. Mark the api key as sensitive data, so that the content of the variable is not visible any more after saving.
4. Genenerate the plan - check the logs
5. Apply the plan - check the logs and take a look in the resource list whether the LogDNA service has been created - hint: use the "burger" navigation menu.
6. Destroy the resources only in the first step - hint: can be found in Actions -> Delete
7. Delete your workspace as final step.
