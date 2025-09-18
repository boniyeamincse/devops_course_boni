# 📘 Course Outline: Terraform – Infrastructure Provisioning

## Module 1: Introduction to Terraform
- What is Infrastructure as Code (IaC)?
- Overview of Terraform and its benefits
- Declarative vs. Imperative configuration
- Terraform vs. other IaC tools (CloudFormation, ARM templates)
- Installing Terraform and basic setup

## Module 2: Terraform Basics
- Understanding HCL (HashiCorp Configuration Language)
- Providers and resources
- Creating your first Terraform configuration
- Planning and applying changes (`terraform plan`, `terraform apply`)
- Destroying infrastructure (`terraform destroy`)

## Module 3: State Management
- What is Terraform state?
- Local vs. remote state
- Configuring remote backends (S3, GCS, Azure, etc.)
- State locking and versioning
- Import existing resources (`terraform import`)

## Module 4: Variables and Outputs
- Defining input variables
- Variable types and validation
- Output values
- Using variable files (`terraform.tfvars`)
- Environment variables and command-line overrides

## Module 5: Modules and Reusability
- Creating and using Terraform modules
- Module sources (local, Git, Terraform Registry)
- Module inputs and outputs
- Best practices for module design
- Version pinning and updates

## Module 6: Data Sources and Provisioners
- Using data sources to query existing resources
- Local and remote provisioners
- File and remote-exec provisioners
- Connection blocks for remote execution
- When to use provisioners vs. configuration management tools

## Module 7: Workspaces and Environments
- Managing multiple environments with workspaces
- Creating and switching workspaces
- Workspace-specific state
- Best practices for multi-environment deployments

## Module 8: Advanced Terraform Features
- Expressions and functions (built-in functions, conditional logic)
- Dynamic blocks
- For-each and count meta-arguments
- Terraform Cloud and Enterprise features
- Policy as Code with Sentinel

## Module 9: Security and Best Practices
- Managing secrets and sensitive data
- Least privilege principles
- Code reviews and collaboration
- Testing Terraform code (unit tests, integration tests)
- CI/CD integration for Terraform

## Module 10: Integration and Real-World Scenarios
- Terraform with AWS, Azure, GCP
- Multi-cloud deployments
- Integration with Ansible, Puppet, Kubernetes
- GitOps with Terraform
- Troubleshooting common issues

## Module 11: Hands-On Projects
- Provisioning a basic web application infrastructure
- Setting up a multi-tier application stack
- Implementing blue-green deployments with Terraform
- Creating reusable modules for common infrastructure patterns
- Building a complete CI/CD pipeline including infrastructure provisioning