# tf-null-provider-sample

This is a basic Terraform example that uses the [`null` provider](https://registry.terraform.io/providers/hashicorp/null/latest/docs) to simulate a resource. It is often used for testing, local-exec commands, or as a placeholder.

## Files
- `main.tf` – Defines the null resource.
- `outputs.tf` – Displays the outputs after creation.

## Usage

```bash
terraform init
terraform apply

## Results
![output]()
