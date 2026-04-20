# Getting started App | Docker Practicee

This repository is a fork of the official Docker getting-started app, used for practicing core containerization, CI/CD, and DevOps concepts.

## Purpose
My goal from this project is to **gain hands-on experience** with:
- Writing optimized Dockerfiles
- Building and Running Containers
- Understanding image layers and caching
- Implementing CI/CD pipelines using GitHub Actions

## 🐳 Docker Setup
#### Build the App
`docker build -t getting-started .`

#### Run a container from the built image
`docker run -d -it -p 3000:3000 --name getstart getting-started`
> The app will be accessed at `http://localhost:3000`

## ⚙️ CI/CD Pipeline
The pipeline, on any push to the main branch, builds the image and pushes it to **GitHub Container Registry**

## Tech Stack
- Node.js
- Docker
- GitHub Actions

> _Learning Never Exhausts the Mind_, Keep Going
