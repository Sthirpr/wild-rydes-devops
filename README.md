# Wild Rydes DevOps Project

This repository contains the infrastructure as code and application source for Wild Rydes' AWS deployment.

## Project Structure

- `app/`: Application source code
- `infrastructure/`: CloudFormation templates
- `buildspec.yml`: CodeBuild configuration
- `appspec.yml`: CodeDeploy configuration
- `Dockerfile`: Container configuration

## Deployment

1. Deploy the CloudFormation stack using the template in `infrastructure/wild-rydes-infra.yml`
2. The CI/CD pipeline will automatically build and deploy changes when pushed to the main branch