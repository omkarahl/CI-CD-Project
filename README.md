# CI-CD-Project

High-Level Architecture
Workflow:
Developer Workflow:
Developer commits code to a GitHub repository.
GitHub triggers a Jenkins job.
Jenkins Workflow:
Jenkins uses Packer to create a new AMI.
Ansible provisions the instance during the Packer build process.
Jenkins deploys the new instance on AWS using the latest AMI.
Jenkins can also handle application deployment.
Tech Stack
Ansible: Configuration management.
Packer: Image creation.
Jenkins: CI/CD pipeline automation.
AWS: Cloud infrastructure.
GitHub: Source control and webhook integration.
