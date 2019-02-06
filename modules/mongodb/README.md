# mongodb - AWS EC2-VPC Security Group Terraform module

## Usage

```hcl
module "mongodb_security_group" {
  source = "terraform-aws-modules/security-group/aws//modules/mongodb"

  # omitted...
}
```

All automatic values **mongodb module** is using are available [here](https://github.com/terraform-aws-modules/terraform-aws-security-group/blob/master/modules/mongodb/auto_values.tf).

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->