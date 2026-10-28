# Kubernetes NGINX Deployment with HPA

A simple Kubernetes project demonstrating container deployment, service exposure, monitoring, and automatic horizontal scaling using Kubernetes HPA.

## 🚀 Project Overview

This project deploys an NGINX web server on a local Kubernetes cluster using Docker Desktop Kubernetes.

It demonstrates:

- Kubernetes Deployment
- Multiple pod replicas
- Kubernetes NodePort Service
- Horizontal Pod Autoscaler (HPA)
- Kubernetes Metrics Server
- CPU-based automatic scaling
- Load testing with BusyBox
- Git and GitHub

## 🛠️ Technologies Used

- Kubernetes
- Docker Desktop
- NGINX
- kubectl
- Metrics Server
- YAML
- Git & GitHub

## 📁 Project Structure

```text
kubernetes-nginx-project/
│
├── k8s/
│   ├── deployment.yaml
│   ├── service.yaml
│   └── hpa.yaml
│
├── metrics-patch.json
└── README.md