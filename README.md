# gh-deployment-workflow
A simple GitHub Actions workflow to deploy a static website to GitHub Pages

# GitHub Actions Deployment Workflow

This project demonstrates how to use GitHub Actions to automatically deploy a static website to GitHub Pages whenever the `index.html` file is updated.

## How It Works
- The `deploy.yml` workflow file in the `.github/workflows` directory defines the CI/CD pipeline.
- Whenever changes are pushed to the `main` branch, GitHub Actions checks if the `index.html` file has been modified.
- If it has, the workflow deploys the updated website to GitHub Pages.

# Project URL
https://roadmap.sh/projects/github-actions-deployment-workflow
