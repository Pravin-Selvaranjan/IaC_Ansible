# Terraform

- In its most basic form, Terraform is an application that converts configuration files known as HCL (Hashicorp Configuration Language) into real world infrastructure, usually in Cloud providers such as AWS, Azure or Google Cloud Platform.
- Infrastructure as Code (IaC) is a widespread terminology among DevOps professionals. It is the process of managing and provisioning the complete IT infrastructure (comprises both physical and virtual machines) using machine-readable definition files. It is a software engineering approach toward operations. It helps in automating the complete data center by using programming scripts.

## Benefits of Terraform?


- Does orchestration, not just configuration management
- Supports multiple providers such as AWS, Azure, GCP, DigitalOcean and many more
- Provide immutable infrastructure where configuration changes smoothly
- Uses easy to understand language, HCL (HashiCorp configuration language)
- Easily portable to any other provider
- Supports Client only architecture, so no need for additional configuration management on a server



## Steps to take in order to utilise Terraform

- 1. Install [Terraform](https://www.terraform.io/downloads)
- 2. Deploy a singler server, Terraform code is written in a language called HCL in files with the extension .tf. It is a declarative language, so your goal is to describe the infrastructure you want, and Terraform will figure out how to create it. Terraform can create infrastructure across a wide variety of platforms, or what it calls providers, including AWS, Azure, Google Cloud, DigitalOcean, and many others.
- 3. The first step to using Terraform is typically to configure the provider(s) you want to use. Create a file called main.tf and put the following code in it:

```
provider "aws" {
  region = "us-east-2"
}
```
- 4. 