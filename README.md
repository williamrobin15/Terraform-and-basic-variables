# Using Basic Variables in Terraform

This Repo demonstrates how to work with **variables in Terraform**. Variables allow you to parameterize your infrastructure code, making it reusable and easier to manage.

## 📂 What’s Included
- **`variables.tf`** → Defines input variables with type, description, and default values.  
- **`main.tf`** → Uses the defined variables in resource configurations.  
- **`terraform.tfvars`** → Provides actual values for the variables.  
- **Command line variables** → Example of passing values using `-var` flag.  

## 🛠️ How to Use

1. Initialize Terraform:
   ```sh
   terraform init
   ```

2. Validate the configuration:
   ```sh
   terraform validate
   ```

3. Plan the infrastructure:
   ```sh
   terraform plan
   ```

4. Apply the configuration:
   ```sh
   terraform apply
   ```

5. Destroy when no longer needed:
   ```sh
   terraform destroy
   ```
