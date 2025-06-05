# Azure DevOps CI/CD Pipeline Demo

This project demonstrates a CI/CD pipeline built with Azure DevOps to deploy a .NET Core web app to Azure App Service. The pipeline includes build, test, and deploy stages, configured using YAML.

## Features
- Automated build and test for .NET Core web app.
- Deployment to Azure App Service with zero downtime.
- Integration with GitHub for source control.

## Setup
1. Clone the repository: `git clone https://github.com/MrGandikota/Azure-CICD-Demo.git`
2. Set up an Azure App Service and resource group.
3. Configure Azure DevOps with your GitHub repo.
4. Update `azure-pipelines.yml` with your Azure subscription and App Service name.
5. Push changes to trigger the pipeline.

## Technologies
- Azure DevOps
- .NET Core
- YAML
- Git