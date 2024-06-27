## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) | >= 1.2 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_aws"></a> [aws](#provider\_aws) | n/a |

## Modules

| Name | Source | Version |
|------|--------|---------|
| <a name="module_allow_group"></a> [allow\_group](#module\_allow\_group) | ./modules/group-policy | n/a |
| <a name="module_tags"></a> [tags](#module\_tags) | cloudopsworks/tags/local | 1.0.9 |

## Resources

| Name | Type |
|------|------|
| [aws_organizations_account.org](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/organizations_account) | resource |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_access_role"></a> [access\_role](#input\_access\_role) | n/a | `string` | `"TerraformRole"` | no |
| <a name="input_allow_group"></a> [allow\_group](#input\_allow\_group) | n/a | `bool` | `false` | no |
| <a name="input_allowsts_group"></a> [allowsts\_group](#input\_allowsts\_group) | n/a | `string` | `"terraform-access"` | no |
| <a name="input_environment_name"></a> [environment\_name](#input\_environment\_name) | n/a | `string` | n/a | yes |
| <a name="input_environment_type"></a> [environment\_type](#input\_environment\_type) | n/a | `string` | n/a | yes |
| <a name="input_extra_tags"></a> [extra\_tags](#input\_extra\_tags) | n/a | `map(string)` | `{}` | no |
| <a name="input_name"></a> [name](#input\_name) | # (c) 2024 - Cloud Ops Works LLC - https://cloudops.works/ On GitHub: https://github.com/cloudopsworks Distributed Under Apache v2.0 License | `string` | `""` | no |
| <a name="input_organization_allow_billing_access"></a> [organization\_allow\_billing\_access](#input\_organization\_allow\_billing\_access) | n/a | `bool` | `true` | no |
| <a name="input_organization_email"></a> [organization\_email](#input\_organization\_email) | n/a | `string` | n/a | yes |
| <a name="input_organization_name"></a> [organization\_name](#input\_organization\_name) | n/a | `string` | n/a | yes |
| <a name="input_organization_parent_id"></a> [organization\_parent\_id](#input\_organization\_parent\_id) | n/a | `string` | `null` | no |
| <a name="input_organization_role"></a> [organization\_role](#input\_organization\_role) | n/a | `string` | `"OrganizationAllowAllAccessAssumeRole"` | no |
| <a name="input_organization_unit"></a> [organization\_unit](#input\_organization\_unit) | n/a | `string` | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_account_arn"></a> [account\_arn](#output\_account\_arn) | n/a |
| <a name="output_account_assume_role_id"></a> [account\_assume\_role\_id](#output\_account\_assume\_role\_id) | n/a |
| <a name="output_account_console_url"></a> [account\_console\_url](#output\_account\_console\_url) | n/a |
| <a name="output_account_id"></a> [account\_id](#output\_account\_id) | # (c) 2024 - Cloud Ops Works LLC - https://cloudops.works/ On GitHub: https://github.com/cloudopsworks Distributed Under Apache v2.0 License |
| <a name="output_account_name"></a> [account\_name](#output\_account\_name) | n/a |
| <a name="output_account_tags"></a> [account\_tags](#output\_account\_tags) | n/a |
