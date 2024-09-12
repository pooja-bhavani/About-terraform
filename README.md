i# About-terraform
Terraform is an open-source Infrastructure as Code (IaC) tool created by HashiCorp. Terraform is an Infrastructure as Code (IaC) tool that automates the creation and management of infrastructure resources. It supports multiple cloud providers, including AWS, Google Cloud Platform (GCP), and Microsoft Azure. By learning Terraform, you gain the ability to manage infrastructure across various cloud platforms using a consistent tool and workflow, avoiding the need to learn each cloud provider's native IaC tools, such as AWS CloudFormation, Azure Resource Manager (ARM) templates, or Google Cloud Deployment Manager.

Multi-Cloud Support: Use the same configuration language to manage resources across different cloud providers.

Consistent Workflow: Standardize infrastructure provisioning and management with a single tool.

Reusability: Create reusable configurations and modules to simplify infrastructure management.

Scalability: Manage large-scale infrastructure efficiently with version control and collaboration features.


# Terraform installation for ubuntu
```
wget -O- https://apt.releases.hashicorp.com/gpg | sudo gpg --dearmor -o /usr/share/keyrings/hashicorp-archive-keyring.gpg
echo "deb [signed-by=/usr/share/keyrings/hashicorp-archive-keyring.gpg] https://apt.releases.hashicorp.com $(lsb_release -cs) main" | sudo tee /etc/apt/sources.list.d/hashicorp.list
sudo apt update && sudo apt install terraform
```
# Terraform installation for linux
```
sudo yum install -y yum-utils shadow-utils
sudo yum-config-manager --add-repo https://rpm.releases.hashicorp.com/AmazonLinux/hashicorp.repo
sudo yum -y install terraform
```
# Terraform installation for macOS
```
brew tap hashicorp/tap
brew install hashicorp/tap/terraform
```
