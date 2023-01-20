# Terraform module | AzureRM - Subnet network security group association

This Terraform module is designed to create a Subnet network security group association for Azure.

## Pre-requisites

Using the modules requires the following pre-requisites:
 * Active Azure account and subscription 

## Usage

`subnet_network_security_group_association`

```hcl
module "subnet_network_security_group_association" {
  source  = "TheIronRock95/subnet_network_security_group_association/azurerm"
  version = "x.x.x"

  network_security_group_id = var.network_security_group_id
  subnet_id                 = var.subnet_id
}

```

## Authors

The module is maintained by [Wouter Damman](https://github.com/TheIronRock95)

## Documentation

> product: https://azure.microsoft.com/en-us/
> 
> Provider: https://registry.terraform.io/providers/hashicorp/azurerm/latest
> 
> Documentation: https://learn.microsoft.com/en-us/azure/?product=popular
