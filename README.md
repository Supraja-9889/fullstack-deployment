
This repository contains configuration and deployment files for a fullstack application.

## 📦 Files Included

| File | Description |
|------|--------------|
| `Dockerfile.frontend` | Builds the frontend container image |
| `Dockerfile.backend` | Builds the backend container image |
| `fullstack-deployment.yaml` | Kubernetes deployment file for the fullstack app |

## ⚙️ Usage

1. **Build Docker Images**
   ```bash
   docker build -t frontend-app -f Dockerfile.frontend .
   docker build -t backend-app -f Dockerfile.backend .
Deploy to Kubernetes
kubectl apply -f fullstack-deployment.yaml
kubectl get pods
