# Static Website + CloudFront + CI/CD

## Project Description
This is a static website hosted on AWS S3 and delivered globally via CloudFront. 
The project includes CI/CD for automated deployment from GitHub via GitHub Actions.


## Folder Structure
- `src/` - Static website files (`index.html`, assets, CSS, JS)
- `.github/workflows/` - CI/CD pipeline files (GitHub Actions)
- `infra/` - Infrastructure as Code (CloudFormation/Terraform/CDK)

## Architecture

<img width="470" height="558" alt="Screenshot 2025-12-12 at 13 42 23" src="https://github.com/user-attachments/assets/3d51af5c-2296-4603-90c7-35e74a612ab2" />

Text Diagram:

          GitHub Actions
                 |
                 v
            S3 Bucket
                 |
                 v
          CloudFront CDN
                 |
                 v
             End Users


## Status

✅ Website deployed and visible via CloudFront

✅ Static website with animations and assets ready

✅ CI/CD pipeline running — changes pushed to main automatically deploy


## CloudFront URL

Visit the CloudFront URL to see the live website with animations and clouds:
https://d1f6t4cm8q2zb7.cloudfront.net/


