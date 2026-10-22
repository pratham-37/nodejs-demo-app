
# Node.js CI/CD Pipeline Using GitHub Actions

## Objective
Automate testing and Docker image publishing for a
Node.js application using GitHub Actions.

## Tools Used
- GitHub
- GitHub Actions
- Node.js
- Docker
- Docker Hub

## Workflow
1. Push code to the main branch.
2. Install Node.js dependencies.
3. Run application tests.
4. Build the Docker image.
5. Push the image to Docker Hub.

## Docker Image
dockerhub-username/nodejs-demo-app:latest

Replace dockerhub-username with your Docker Hub username.

## Run Locally
npm install
npm test
npm start

Open http://localhost:3000 in your browser.

## Result
The workflow automatically tests the application and
publishes a Docker image when the test job succeeds.
