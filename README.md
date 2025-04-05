# Jenkins CI/CD Pipeline for Python App

This project demonstrates how to build, test, and deploy a simple Python application using Jenkins and Docker in a full CI/CD pipeline.

#Tech Stack

- Python 3
- Docker & Docker Compose
- Jenkins (Declarative Pipeline)
- Git & GitHub

# How It Works

1. Jenkins checks out the code from GitHub.
2. Builds a Docker image from `dockerfile`.
3. (Optional) Runs tests — you can add unit tests later.
4. Deploys the container using `docker-compose`.

# Run Locally

```bash
docker-compose up --build



