Create a directory for your Terraform project and create a Terraform configuration file (usually named main.tf) in that directory.
In this file, you define the AWS provider and resources you want to create. 
provider "aws" {
  region     = "ap-south-1"
 }
resource "aws_instance" "web" {
  ami           = ami-04f8d7ed2f1a54b14 # Specify appropriate ami id
  instance_type = "t2.micro"
