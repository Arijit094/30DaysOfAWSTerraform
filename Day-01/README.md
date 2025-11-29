# ⭐ Day 1: Introduction to Terraform


## 📚 Topics Covered

Understanding Infrastructure as Code (IaC)

Why we need IaC

What is Terraform and its benefits?

Challenges with the traditional approach

Terraform Workflow

Installing Terraform

## 🧠 Key Learning Points
### 🔹 What is Infrastructure as Code?

Provisioning your infrastructure through code instead of manual processes.

### 🔹 Why Infrastructure as Code?

Consistency: Identical environments across dev, staging, production

Time Efficiency: Automated provisioning saves hours

Cost Management: Track costs & automate cleanup

Scalability: Deploy hundreds of servers with same effort

Version Control: Track changes using Git

Reduced Human Error: Avoid manual configuration mistakes

Collaboration: Teams work efficiently on infra

## Benefits of IaC

Consistent environment deployment

Easy cost management

Write once, deploy anywhere

Time-saving automation

Reduced human error

Cost optimization

Git-based version control

Automated cleanup

Developers focus on building apps

Easy to replicate production for debugging


## 🌍 What is Terraform?

Terraform is an Infrastructure as Code tool used to automate provisioning and management of resources across multiple cloud providers.


⚙️ How Terraform Works
Write Terraform files → Run Terraform commands → AWS APIs through Provider


## 🔄 Terraform Workflow Phases

terraform init        # Initialize working directory
terraform validate    # Validate configuration files
terraform plan        # Preview execution plan
terraform apply       # Apply changes to reach the desired state
terraform destroy     # Destroy infrastructure


## 🧪 Tasks for Practice
### ✔️ Install Terraform

Official Guide: https://developer.hashicorp.com/terraform/install

## ✔️ Common Installation Commands
For macOS
`brew install hashicorp/tap/terraform`

## ✔️ Setup Commands
```
terraform -install-autocomplete

alias tf=terraform

terraform -version

```
