# Introduction
Terraform module for setting up an AWS S3/DynamoDB Terraform backend.

# Modifications
* Added KMS key alias resource to 'replica.tf' and 'variables.tf'- assists with creating a more generic replica IAM policy

# Credits
* Code inspiration
  * https://registry.terraform.io/modules/nozaq/remote-state-s3-backend/aws/latest
  * https://github.com/nozaq/terraform-aws-remote-state-s3-backend

# References
* https://www.terraform.io/language/settings/backends/s3
* https://medium.com/@vijith.vijay7777/concourse-terraform-aws-1d128d5b49b1
* https://registry.terraform.io/namespaces/terraform-aws-modules
* https://registry.terraform.io/modules/nozaq/remote-state-s3-backend/aws/latest
* https://github.com/ozbillwang/terraform-best-practices
