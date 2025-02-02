## OpenShift Kustomize Deployment

This repository contains Kustomize configurations for deploying MySQL and Nginx in OpenShift.
# Project Structure

The project is organized in the following way:
. ├── base │ ├── deployment.yaml │ ├── kustomization.yaml │ ├── nginx-deployment.yaml │ ├── nginx-service.yaml │ └── service.yaml ├── overlays │ └── dev │ ├── deployment.yaml │ ├── kustomization.yaml │ ├── nginx-deployment.yaml │ ├── nginx-service.yaml │ └── service.yaml └── README.md

- **base**: Contains the common deployment and service configurations for MySQL and Nginx.
- **overlays/dev**: Contains the environment-specific configuration for the dev environment, which overrides the base configuration.
- **README.md**: This file.
