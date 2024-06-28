Create a directory for your Terraform project and create a Terraform configuration file (usually named ``main.tf``) in that directory.
In this file, you define the AWS provider and resources you want to create.
```
provider "aws" {
  region     = "ap-south-1"
 }
 
resource "aws_instance" "web" {
  ami           = "ami-04f8d7ed2f1a54b14"  # Specify appropriate ami id
  instance_type = "t2.micro"
  }
  ```
* Launch an EC2 instance manually
![image](https://github.com/pooja-bhavani/About-terraform/assets/147735975/26225f67-5689-4576-bd75-0b99ed38d16f)
* Install Terraform, create a directory and run terraform init to initialize the dir 
![image](https://github.com/pooja-bhavani/About-terraform/assets/147735975/d342aec9-8849-4cc0-99b1-68396d9eb436)
* Create a file maned main.tf or any other named file but with .tf write the provider and specify the resource you want to create and run terraform
![image](https://github.com/pooja-bhavani/About-terraform/assets/147735975/93ab279b-4bef-459a-a6c7-445e421f4dd7)
* Run terraform validate to see if there is any error in the file before runinng terraform apply and then run terraform apply 
![image](https://github.com/pooja-bhavani/About-terraform/assets/147735975/9d113818-15ee-4ddc-b5f8-fbe9e932d540)
![image](https://github.com/pooja-bhavani/About-terraform/assets/147735975/36838aa6-2de9-4c44-bf23-4c304008480e)
* The resource will be created
![image](https://github.com/pooja-bhavani/About-terraform/assets/147735975/d4cd7801-305b-41a2-bb88-034838ee182b)
*
![image](https://github.com/pooja-bhavani/About-terraform/assets/147735975/7998fb9a-121e-4e70-a375-f592208ad766)
* To terminate the resource run terraform destroy
![image](https://github.com/pooja-bhavani/About-terraform/assets/147735975/fd088000-4940-4311-9f3c-d6353955ab39)









