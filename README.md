This repository demonstrates how to build a CI/CD pipeline using GitHub Actions and AWS CodeDeploy to automatically deploy a web application to an AWS EC2 instance.

Live Demo: http://18.205.1.48/


## Tech Stack
- GitHub Actions
- AWS CodeDeploy
- AWS EC2
- AWS S3
- IAM (OIDC Authentication)
- Nginx



## CI/CD Workflow

1. Push code to the `main` branch.
2. GitHub Actions builds the project.
3. The deployment package is uploaded to Amazon S3.
4. AWS CodeDeploy deploys the application to an EC2 instance.
5. Nginx serves the deployed application.
