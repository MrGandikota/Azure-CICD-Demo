# Azure DevOps CI/CD Pipeline Demo
This project showcases a CI/CD pipeline built with Azure DevOps to deploy an ASP.NET Core web app to Azure App Service. The app displays a professional resume, demonstrating expertise in DevOps, CI/CD automation, and Azure cloud services. View the deployed app at https://gandikotademo.azurewebsites.net/.
Source code: https://github.com/MrGandikota/Azure-CICD-Demo

# Features
Automated CI/CD pipeline using Azure DevOps.
Zero-downtime deployment to Azure App Service.
Resume web page styled with Tailwind CSS.
GitHub integration for source control.

# Setup
Clone the repository: git clone https://github.com/MrGandikota/Azure-CICD-Demo.git
Create an Azure App Service and resource group in the Azure Portal.
Set up an Azure DevOps project and connect the repository.
Configure the service connection in Azure DevOps using a managed identity with Web App Contributor role.
Run the pipeline (azure-pipelines.yml) to deploy the app.

# Technologies
- Azure DevOps
- ASP.NET Core
- Tailwind CSS
- Azure App Service
- GitHub

# Troubleshooting
Service Connection: Ensure the Azure DevOps service connection has appropriate permissions.
Parallelism: Verify Microsoft-hosted parallel jobs are available or request a grant at https://aka.ms/azpipelines-parallelism-request.
Deployment: Check pipeline logs for errors if the app fails to deploy.

