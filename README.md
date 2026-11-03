# devops-capstone-project

![Build Status](https://github.com/YOUR-USERNAME/devops-capstone-project/actions/workflows/ci-build.yaml/badge.svg)

## Project Description

This capstone project is a **Customer Accounts microservice** for an e-commerce website. It provides a RESTful API, built with Python and Flask, that other microservices can call to manage customer account data such as names and addresses.

The project demonstrates a complete DevOps workflow:

- **Agile planning** using GitHub Projects, user stories, and sprints
- **REST API** with Create, Read, Update, Delete, and List endpoints
- **Automated testing** with nosetests, plus code quality checks with Flake8 and Pylint
- **Continuous Integration** using GitHub Actions
- **Security** with Talisman security headers and CORS policies
- **Containerization** using Docker
- **Deployment** to Kubernetes, automated with a Tekton CD pipeline

## Tech Stack

- Python 3 / Flask
- SQLAlchemy / PostgreSQL
- GitHub Actions
- Docker
- Kubernetes / OpenShift
- Tekton

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/accounts` | Create a new account |
| GET | `/accounts` | List all accounts |
| GET | `/accounts/{id}` | Read an account |
| PUT | `/accounts/{id}` | Update an account |
| DELETE | `/accounts/{id}` | Delete an account |

## Author

YOUR NAME
