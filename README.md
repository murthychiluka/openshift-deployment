# Project Overview

#  change the namespace according to your project

This repository is organized into several directories, each serving a specific purpose for deployment, CI/CD, and monitoring.

## Directory Structure

- **CICD/**
  - Contains CI/CD pipeline configurations (e.g., `hotstar-pipeline.yaml`).
  - Use these files with your CI/CD tool to automate build and deployment processes.

- **FULLSTACK-DEPLOYMENT/**
  - Contains build and deployment configurations for the full stack application (e.g., `build.yaml`, `dc.yaml`).
  - Use these files to build and deploy the application using your preferred orchestration or CI/CD tool.

- **MONITORING/**
  - Contains monitoring and observability configurations (e.g., `kibana-deploy.yaml`).
  - Use these files to deploy monitoring tools like Kibana to your cluster or monitoring stack.


# Note

change the namespace details in every yaml file 

## Getting Started

1. Review the README.md in each directory for specific instructions.
2. Apply or integrate the YAML files as needed for your environment.
3. Customize configurations to fit your infrastructure and workflow.

---

For more details, see the individual README.md files in each directory.

