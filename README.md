# Automated CI/CD Pipeline Using Jenkins and AWS EC2

## Project Overview
This project demonstrates an automated CI/CD pipeline using Jenkins, GitHub, and AWS EC2.

Whenever a developer pushes new code to GitHub, a GitHub Webhook triggers Jenkins automatically. Jenkins pulls the latest code and deploys the updated website to the Apache web server running on an AWS EC2 Ubuntu instance.

## Objectives
- Automate application deployment.
- Integrate Jenkins with GitHub.
- Configure GitHub Webhooks.
- Deploy website updates automatically.
- Understand CI/CD pipeline implementation.

## Technologies Used
- AWS EC2
- Ubuntu Linux
- Jenkins
- Git and GitHub
- Apache Web Server
- HTML and CSS
- Shell Scripting
- GitHub Webhooks

## Architecture / Workflow

Developer → GitHub → GitHub Webhook → Jenkins Pipeline → Checkout → Deploy → Apache Web Server → Live Website

## Implementation Steps
1. Launched an Ubuntu EC2 instance on AWS.
2. Installed Java and Jenkins.
3. Installed Apache and Git.
4. Created a GitHub repository.
5. Added HTML and CSS website files.
6. Created a Jenkinsfile with Checkout, Deploy, and Verify stages.
7. Configured Jenkins to pull source code from GitHub.
8. Configured GitHub Webhook to trigger Jenkins automatically.
9. Deployed the updated website to the Apache web server.
10. Verified automatic deployment after pushing new code to GitHub.

## Pipeline Stages

**Checkout:** Retrieves the latest source code from GitHub.

**Deploy:** Copies website files to the Apache web root directory.

**Verify:** Confirms deployment completion.

## Final Output
Successfully implemented an automated CI/CD pipeline. Website updates are automatically deployed to AWS EC2 whenever new code is pushed to GitHub.

## Screenshots
Project screenshots are available in the `screenshots` folder.

## Author
Sakshi
