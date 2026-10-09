# AWS Cloud Resume Challenge

Live site: https://[your-cloudfront-url]

## Architecture
- **S3**: hosts the static resume site
- **CloudFront**: serves it over HTTPS
- **Lambda + DynamoDB**: serverless visitor counter
- **Terraform**: infrastructure as code
- **GitHub Actions**: auto-deploys on every push and clears the CloudFront cache

## What I learned
- [One line about Terraform]
- [One line about CI/CD]
- [One line about IAM permissions]