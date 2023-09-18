# Writing Good Documentation.

## *Fenced Code Blocks*

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

> Take note of the where the backtick button is located on the Keyboard.

> It should appear above the tab key, but this may vary depending on your keyboard layout.


![backtick](https://github.com/S47sawan/github-docs-example/assets/87205154/cd7c9e18-464e-431f-9b3d-556be350a3fc)

## *Highlight Syntax* <sup>[1]</sup>

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
## *Use Github Flavoured Markdown Task Lists* <sup>[2]</sup>
Github extends Markdown to have a list where you can check off items as you go along. 

- [X] Finish step 1
- [ ] Finish step 2
- [ ] Finish step 3
      
## *Use Emojis* (optional)

Github Flavoured Markdown support emojis.Here are some examples!

code
```md
 - :smile:
 - :star:
 - :rocket:
 - :cloud:
 - :computer:
```
Emojis
 - :smile:
 - :star:
 - :rocket:
 - :cloud:
 - :computer:

## *Using Tables*
You can create tables with pipes <span>&#x007C;</span> and hypens - 

Code
````markdown
| Name | Syntax | emoji |
| :--- |:---: |  ---: |
| Cloud |`:cloud:`| ☁️ |
| Desktop_computer |`:desktop_computer:`| 🖥️ |
````
Table
| Name | Syntax | emoji |
| :--- |:---: |  ---: |
| Cloud |`:cloud:`| ☁️ |
| Desktop_computer |`:desktop_computer:`| 🖥️ |

## *References*
- [Basic writing and formatting syntax (Github Flavoured Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [Creating and highlighting code blocks](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks) <sup>[1]</sup>
- [emoji-cheat-sheet](https://github.com/ikatyang/emoji-cheat-sheet) <sup>[2]</sup>
