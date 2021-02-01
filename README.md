# terraform-christmas-tree-random
A module for https://registry.terraform.io/providers/cappyzawa/christmas-tree/latest

## Requirements

| Name | Version |
|------|---------|
| terraform | >=0.13.0 |
| christmas-tree | >= 0.3.0 |
| rondom | >= 3.0.0 |

## Providers

| Name | Version |
|------|---------|
| christmas-tree | >= 0.3.0 |
| random | n/a |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| tree\_path | Generates Tree into specified path | `string` | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| tree | Ouputs tree generated by resource. |

