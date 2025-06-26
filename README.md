# CI/CD Pipeline with GitHub Actions & Docker

This project sets up an end-to-end CI/CD pipeline using **GitHub Actions** and **Docker**. It automates building, testing, and deploying a simple Python Flask application to DockerHub whenever code is pushed to the main branch.


## Introduction

Continuous Integration and Continuous Deployment (CI/CD) are essential for efficient software delivery. This project demonstrates how to automate container builds and deployments using GitHub Actions.


## Tools Used

- **GitHub Actions** – For automating the CI/CD pipeline  
- **Docker & DockerHub** – For containerization and image hosting   
- **Local system with Docker** – For running the app

## Steps Involved
### Created the Flask App and requirements.txt <br>
### Added dependencies to requirements.txt
### Dockerized the application
### Created GitHub Actions workflow at .github/workflows/docker-ci-cd.yml
### Configured GitHub Secrets
### Pushed Code to GitHub
![](https://github.com/deepakbehera11/Ci-Cd-Pipeline-With-GithubActions-and-Docker/blob/2e043f1b051689d068c77d9f44e684c8e65c0230/assets/Screenshot-01.png)
### Pulled & Ran the Image
![](https://github.com/deepakbehera11/Ci-Cd-Pipeline-With-GithubActions-and-Docker/blob/2e043f1b051689d068c77d9f44e684c8e65c0230/assets/Screenshot-local.png)
