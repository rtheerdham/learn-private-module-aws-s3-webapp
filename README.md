# Learn Private Module Registry

The companion repository for the [Learn guide](https://learn.hashicorp.com/terraform/modules/private-modules) on using the private module registry in Terraform Cloud.

~~~
module "example" {
  source  = "app.terraform.io/tj-org/example/aws"
  version = "1.0.0"
  # insert required variables here
}
~~~