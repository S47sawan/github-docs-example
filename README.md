# Writing Good Documentation.

## Fenced Code Blocks

Why use fenced code blocks?
- Allows developers to easily copy paste from the documentation. As the code is ready to use it reduces syntax errors and saves time.
- Helps to maintain consistent formatting and indentation for code examples across documentation.

How do I Fence Code blocks?
  
  This can be achieved by using *triple backticks*  ( ``` )

```
  # Create a VPC
    resource "aws_vpc" "example_vpc" {
      cidr_block = "10.0.0.0/16"  # Adjust the CIDR block as needed
      enable_dns_support = true
      enable_dns_hostnames = true
```
  
Shortcut on keyboard {ctrl} + E

![backtick](https://github.com/S47sawan/github-docs-example/assets/87205154/cd7c9e18-464e-431f-9b3d-556be350a3fc)

## Highlight Syntax

To highlight syntax for ease understanding, simply add the language (e.g terraform,python,ruby) next to the **top** _backticks_ as shown below.

In my case I have used terraform to write the VPC code.
````
```terraform
  # Create a VPC
    resource "aws_vpc" "example_vpc" {
      cidr_block = "10.0.0.0/16"  # Adjust the CIDR block as needed
      enable_dns_support = true
      enable_dns_hostnames = true
```
````
The result will be a highlighted code as shown below!
```terraform
  # Create a VPC
    resource "aws_vpc" "example_vpc" {
      cidr_block = "10.0.0.0/16"  # Adjust the CIDR block as needed
      enable_dns_support = true
      enable_dns_hostnames = true
```
