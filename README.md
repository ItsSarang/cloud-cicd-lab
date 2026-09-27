# CI/CD Pipeline Using Jenkins, Docker and AWS EC2

A practical demonstration of a CI/CD pipeline using **GitHub, Jenkins, Docker, and AWS EC2**.

This repository was created as part of the **Cloud Computing and DevOps** practical work at **MIT World Peace University (MIT-WPU)**.

<br></br>

## Student

**Sarang Nair**  
B.Tech — MIT World Peace University (MIT-WPU)

<br></br>

## Practical

**Experiment 5 — CI/CD Pipeline Using Jenkins**

The practical demonstrates how a Flask application can be automatically cloned from GitHub, built into a Docker image, and deployed on an AWS EC2 instance using Jenkins.

<br></br>

## CI/CD Flow

```text
Developer
    ↓
GitHub Repository
    ↓
GitHub Webhook
    ↓
Jenkins Pipeline
    ↓
Clone → Build → Deploy
    ↓
Docker Container
    ↓
Flask Web Application
    ↓
AWS EC2
