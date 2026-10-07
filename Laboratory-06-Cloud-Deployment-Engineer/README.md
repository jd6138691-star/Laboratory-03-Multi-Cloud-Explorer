

# Laboratory 06 - Cloud Deployment Engineer

## Mission Overview

This laboratory focuses on deploying a multi-container cloud application using Docker Compose. The project demonstrates a two-tier architecture consisting of a Nextcloud application container and a MariaDB database container.

The infrastructure is defined using Infrastructure as Code (IaC) through a `docker-compose.yml` configuration file.

## Objectives

- Understand the concepts of multi-tier architecture.
- Identify the roles of the application and database tiers.
- Create a Docker Compose configuration file.
- Deploy multiple containers using Docker Compose.
- Configure communication between application and database containers.
- Access a containerized web application through port 8080.
- Properly stop and remove the deployed containers.
- Document the deployment process using Markdown.
- Maintain evidence of the deployment using screenshots.

## Commands Executed

### Create the project directory

```bash
mkdir nextcloud-deployment
cd nextcloud-deployment
