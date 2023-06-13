# dependabot-with-aws-codeartifact
This repo contains the GitHub action that updated the Dependabot secret with a fresh token every 12 hours.

1. [Connect to AWS using OIDC](https://docs.github.com/en/actions/deployment/security-hardening-your-deployments/configuring-openid-connect-in-amazon-web-services)
2. Fetch the token using AWS CLI
3. Update the dependabot token using GitHub CLI

