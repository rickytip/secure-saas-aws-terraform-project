# secure-saas-aws-terraform-project
This project is my Terraform-driven recreation of an AWS SaaS application workshop. Instead of clicking through the console, I’m writing every component as code—identity, storage, APIs, automation, and frontend delivery. The goal is to build deep understanding of AWS security patterns while improving my Terraform skills
📌 Project Goals

- Rebuild a full SaaS-style architecture using Terraform instead of the AWS console

- Learn how identity, APIs, serverless, storage, and automation work together

- Practice least-privilege IAM, secure API patterns, and tenant-aware design

- Improve my Terraform structuring, modules, and automation skills

🏗️ Architecture Overview

This project is based on the AWS SaaS architecture pattern and includes:

- Cognito for user authentication and tenant separation

- API Gateway secured with a Lambda Authorizer

- Lambda functions implementing backend logic

- DynamoDB for tenant and application data

- Verified Permissions for fine-grained authorization

- S3 + CloudFront for secure frontend hosting

- Step Functions for onboarding automation and workflows

- SSM Parameter Store for secure configuration and secret management

  ![3E91A617-09D1-4669-B2E5-2209CF190D8F](https://github.com/user-attachments/assets/2cbca992-2a97-4912-8461-cbdba0d809a5)

