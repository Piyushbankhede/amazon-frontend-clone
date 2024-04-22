# Amazon Frontend Clone

This project aims to create a clone of the Amazon frontend using various technologies including Terraform, AWS EC2 instances, Jenkins, Trivy, OWASP, Docker, Git, and SonarQube.

## Table of Contents

- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

The Amazon Frontend Clone project leverages Terraform to provision AWS EC2 instances, replicating the infrastructure required to host the frontend application. Jenkins is used for continuous integration and deployment, while Trivy and OWASP help ensure container and application security. Docker is utilized for containerization, Git for version control, and SonarQube for code quality analysis.

## Technologies Used

- **Terraform**: Infrastructure as code tool used to provision AWS resources.
- **AWS EC2**: Virtual servers in the AWS cloud used to host the frontend application.
- **Jenkins**: Automation server used for continuous integration and deployment.
- **Trivy**: Vulnerability scanner for containers, used to ensure container security.
- **OWASP**: Open Web Application Security Project, used for application security testing.
- **Docker**: Containerization platform used to package the application and its dependencies.
- **Git**: Version control system used for collaboration and version management.
- **SonarQube**: Code quality analysis tool used to ensure code quality and maintainability.

## Setup

1. **Clone the Repository**: 
   ```bash
   git clone <repository_url>

   
## Install Dependencies:
Install Terraform: Terraform Installation Guide
Install Docker: Docker Installation Guide
Install Jenkins: Jenkins Installation Guide
Install Trivy: Trivy Installation Guide
Install SonarQube: SonarQube Installation Guide
## Configure AWS Credentials:
Ensure that your AWS credentials are configured either through environment variables or AWS CLI.
## Configure Jenkins:
Set up Jenkins with necessary plugins and configure pipelines for CI/CD. Refer to Jenkins documentation for detailed setup instructions.
## Set Up SonarQube:
Configure SonarQube for code quality analysis. Refer to SonarQube documentation for detailed setup instructions.
## Usage
Deploy Infrastructure:
Use Terraform to provision AWS EC2 instances and other necessary resources.<br>
  terraform init<br>
  terraform apply
Build and Deploy Application:
Use Jenkins pipelines to build and deploy the frontend application.
Ensure that Docker containers are built with security scanning using Trivy.
Integrate OWASP testing into the deployment pipeline to ensure application security.
Code Quality Analysis:
Utilize SonarQube for code quality analysis. Integrate SonarQube scans into Jenkins pipelines for continuous monitoring of code quality.
