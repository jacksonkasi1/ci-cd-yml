# backend

## Getting Started

This repository contains the code for the backend project. The code can be deployed using GitLab CI/CD on Railway. 

#### To deploy the code, follow these steps:

1. **Set up GitLab CI/CD environment:**
   - Add the following environment variables in your GitLab CI/CD environment settings:
   
     - `RAILWAY_TOKEN`: This variable should contain your Railway token. Example: `60a0eb49-xxxxx-xxxxx-xxxxx-xxxxx` ( **get from railway.app > project (project name) > project setting > Tokens** )
   
   These environment variables will be used by the GitLab CI/CD pipeline to authenticate with Railway.

2. **Trigger the deployment:**
   - Commit and push your code **integration** to the repository.
   - The GitLab CI/CD pipeline will automatically trigger the deployment process using the specified environment variables.
   - Monitor the pipeline in the GitLab interface to track the deployment status and view any logs or errors.


####  For more details on setting up GitLab CI/CD with Railway, you can refer to the following resources:

- [GitLab CI/CD Guide](https://blog.railway.app/p/gitlab-ci-cd)

If you prefer to use GitHub Actions instead of GitLab CI/CD, you can check out the following resource:

- [GitHub Actions Guide](https://blog.railway.app/p/github-actions)

