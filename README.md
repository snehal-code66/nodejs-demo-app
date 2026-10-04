# Task 1 — Automate Code Deployment Using CI/CD Pipeline (GitHub Actions)

## 📌 Objective

The objective of this task was to automate code deployment using a CI/CD pipeline with **GitHub Actions** for a sample Node.js application.

## 🛠️ Tools Used

* Git
* GitHub
* GitHub Actions
* Node.js
* Docker
* Docker Hub

## 🔧 Work Performed

1. Created a sample Node.js application.
2. Created a GitHub Actions workflow using:
   `.github/workflows/main.yml`
3. Configured the workflow to run automatically on every push to the `main` branch.
4. Added CI/CD jobs for:

   * Testing the application
   * Building the Docker image
   * Pushing the Docker image to Docker Hub
   * Testing/verifying the deployment workflow
5. Created a Dockerfile for containerizing the Node.js application.
6. Built the Docker image using the GitHub Actions workflow.
7. Pushed the Docker image to Docker Hub.
8. Verified the successful execution of the GitHub Actions pipeline.

## 📂 Important Files

```text
.github/
└── workflows/
    └── main.yml

Dockerfile
package.json
package-lock.json
README.md
```

## 🔄 CI/CD Workflow

```text
Code Push to Main
       ↓
GitHub Actions Trigger
       ↓
Test Application
       ↓
Build Docker Image
       ↓
Push Image to Docker Hub
       ↓
Verify Deployment
```

## ✅ Result

The CI/CD pipeline was successfully automated using GitHub Actions. The workflow is triggered by a push to the `main` branch, tests and builds the Node.js application, and pushes the Docker image to Docker Hub.
