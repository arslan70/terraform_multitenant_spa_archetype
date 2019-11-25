# terraform_multitenant_spa_archetype
A quick start terraform template for a multitenant single page application using cognito, api gateway, lambda, dynamodb and S3.

Registration and Authenticaion will be delegated to congnito and dynamodb
Api Gateway and Lambda will be used for authorization and backend APIs
S3 will host the front

This is a serverless solution where all the scalability and uptime is delegated to AWS.

Terraform is used as a IAC tool.
Terragrunt is used as a wrapper to simplify terraform complexities.

# References
https://github.com/aws-quickstart/saas-identity-cognito
https://github.com/squidfunk/terraform-aws-cognito-auth
