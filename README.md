This project demonstrates the complete lifecycle of building, containerizing, and deploying a Go web application using modern DevOps practices.

The application is packaged with Docker, deployed to Kubernetes using both native manifests and Helm charts, and automated through GitHub Actions CI/CD pipelines. The project showcases cloud-native application deployment, container orchestration, and infrastructure automation workflows commonly used in production environments.

---

## Architecture

```text
Developer Push
      │
      ▼
 GitHub Repository
      │
      ▼
 GitHub Actions
      │
      ├── Run Unit Tests
      ├── Build Docker Image
      ├── Validate Kubernetes Manifests
      └── Package Helm Chart
      │
      ▼
 Docker Image
      │
      ▼
 Kubernetes Cluster
      │
      ▼
 Go Web Application
```

---

## Features

### Application Development

* REST-based Go web application
* Static content serving
* Unit testing with Go testing framework
* Modular project structure

### Containerization

* Dockerized application deployment
* Reproducible build process
* Lightweight container images

### Kubernetes Deployment

* Kubernetes manifests for application deployment
* Service definitions
* Scalable container orchestration

### Helm Package Management

* Helm chart for simplified deployments
* Environment-specific configuration support
* Version-controlled application releases

### CI/CD Automation

* GitHub Actions workflow automation
* Automated testing pipeline
* Build validation
* Deployment-ready artifacts

---

## Tech Stack

### Backend

* Go (Golang)

### Containerization

* Docker

### Container Orchestration

* Kubernetes

### Package Management

* Helm

### CI/CD

* GitHub Actions

### Version Control

* Git
* GitHub

---

## DevOps Workflow

1. Developer pushes code to GitHub.
2. GitHub Actions executes automated validation and testing.
3. Docker image is built from the application source.
4. Kubernetes deployment manifests are validated.
5. Helm charts are packaged and prepared for release.
6. Application is deployed to a Kubernetes cluster.

---

## Skills Demonstrated

* Go Application Development
* Docker Containerization
* Kubernetes Deployments
* Helm Chart Development
* GitHub Actions CI/CD
* Container Orchestration
* DevOps Automation
* Cloud-Native Application Delivery


