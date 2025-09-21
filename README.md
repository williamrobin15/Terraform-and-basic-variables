# Using Basic Variables in Terraform

This example demonstrates how to work with **variables in Terraform**. Variables allow you to parameterize your infrastructure code, making it reusable and easier to manage.

## 📂 What’s Included
- **`variables.tf`** → Defines input variables with type, description, and default values.  
- **`main.tf`** → Uses the defined variables in resource configurations.  
- **`terraform.tfvars`** → Provides actual values for the variables.  
- **Command line variables** → Example of passing values using `-var` flag.  

## 🛠️ How to Use

1. Initialize Terraform:

   terraform init


2. Validate the configuration:


   terraform validate


3. Plan the infrastructure:

   terraform plan
 

4. Apply the configuration:


   terraform apply


5. Destroy when no longer needed:

   terraform destroy

