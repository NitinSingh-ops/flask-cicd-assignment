# Flask CI/CD Assignment

## Project Overview

This project demonstrates a CI/CD pipeline implementation using:

* Jenkins
* GitHub Actions
* Python Flask Application
* Pytest

## Repository

GitHub Repository:
https://github.com/NitinSingh-ops/flask-cicd-assignment

## Jenkins Pipeline

The Jenkins pipeline consists of three stages:

### Build

Installs application dependencies.

### Test

Executes automated tests using pytest.

### Deploy

Deploys the application to a staging environment.

Pipeline is automatically triggered through Jenkins.

## GitHub Actions Workflow

Workflow file:

.github/workflows/ci-cd.yml

The workflow performs:

1. Checkout source code
2. Setup Python environment
3. Install dependencies
4. Run automated tests
5. Deploy application

## Prerequisites

* Python 3.x
* Git
* Docker Desktop
* Jenkins Docker Container
* GitHub Account

## Test Execution

Run locally:

python -m pytest -v

## Author

Nitin Prakash Singh
