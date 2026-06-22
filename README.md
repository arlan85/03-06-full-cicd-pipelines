# 03_06 Challenge: Build a Full CI/CD Pipeline

In this challenge, you’ll take a **misconfigured CI/CD pipeline** and transform it into a **clear, ordered continuous deployment workflow**. The pipeline already includes jobs for integration, artifact creation, testing, and deployments to multiple environments—but the jobs run **out of order** and lack **deployment protection** for production.

Your task is to correct the execution flow by adding job dependencies and then secure the production deployment using a **protected environment with required approvals**.

By the end of this challenge, you’ll have a working pipeline that progresses cleanly from commit to production and pauses for manual approval before deploying to a protected environment.

## Challenge Tasks

To complete this challenge, you will:

- Create a new GitHub repository for the exercise
- Upload the provided pipeline and README files
- Move the workflow into the correct GitHub Actions directory
- Observe an incorrectly ordered pipeline execution
- Add job dependencies to create a proper deployment flow
- Configure a protected production environment
- Verify that production deployments require manual approval

This challenge should take **20–30 minutes** to complete.

<!-- FooterStart -->
---
[← 03_05 Continuous Deployment for Infrastructure as Code](../03_05_cd_for_iac/README.md) | [03_07 Solution: Build a Full CI/CD Pipeline →](../03_07_solution_cicd_pipeline/README.md)
<!-- FooterEnd -->
