**AWS Static Website Deployment with Terraform**

**Overview**
Deploys a static stock market website (index.html, error.html) to an AWS S3 bucket using Terraform.

**Deployment Commands**

Initialize Terraform:
terraform init

Preview Changes:
terraform plan -auto-approve
Deploy:
terraform apply -auto-approve

Type yes to confirm.

Access Website:Check output for website_url (e.g., http://my-stock-market-info-abcdef.s3-website-us-east-1.amazonaws.com).


Cleanup
terraform destroy -auto-approve

