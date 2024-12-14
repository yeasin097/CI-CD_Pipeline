# Node.js CI/CD Pipeline Example

This project demonstrates a simple Node.js application with a CI/CD pipeline using GitHub Actions and Docker.

## Prerequisites

- Docker
- Docker Compose
- Node.js

## Setup

1. Clone this repository.
2. Install dependencies:

\`\`\`bash
npm install
\`\`\`

3. Start the application locally:

\`\`\`bash
npm start
\`\`\`

4. For CI/CD, GitHub Actions will handle testing, Docker image building, and deployment to staging.

## Secrets Required

- \`DOCKER_USERNAME\`
- \`DOCKER_PASSWORD\`
- \`DB_HOST\`
- \`DB_USER\`
- \`DB_PASSWORD\`
- \`DB_NAME\`

Ensure these are set in GitHub repository secrets.
