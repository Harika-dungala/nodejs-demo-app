# NodeJS Demo App

This is a simple Node.js web app used to demonstrate CI/CD automation with **GitHub Actions** and **DockerHub**.

## Project Structure

devops-pipeline-project/
├── server.js
├── package.json
├── Dockerfile
└── .github/
    └── workflows/
        └── main.yml


## 🚀 Steps Performed
1. Created a simple Node.js app (`src/index.js`)
2. Added a Dockerfile to containerize the app
3. Created a GitHub Actions workflow (`.github/workflows/main.yml`)
4. Configured CI/CD to:
   - Test
   - Build
   - Push Docker image to DockerHub

## 🧰 Tech Stack
- Node.js
- Docker
- GitHub Actions

## Project Setup (Git Bash Commands)

### 1. Create Project Folder & Initialize Node.js

```bash
# Create project folder on Desktop
cd ~/Desktop
mkdir devops-pipeline-project
cd devops-pipeline-project

# Initialize Node.js project
npm init -y
npm install express


## 🧪 Run locally
```bash
npm install
npm start
