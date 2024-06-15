# AWS VPC module for Terraform

A lightweight VPC module for Terraform.

## Usage

```hcl
module "vpc_basic" {
  source = "https://github.com/kessiey/tf_vpc_basic.git"

  name = "vpc_name"

  cidr = "10.0.0.0/16"
  public_subnet = "10.0.1.0/24"
}
```

See `interface.tf` for additional configurable variables.

## License

MIT

