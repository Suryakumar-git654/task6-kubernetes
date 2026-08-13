@"
# Task 6 - Kubernetes & Helm Deployment

## Project Overview

This project demonstrates Kubernetes deployment and Helm-based application management using Minikube.

## Technologies Used

- Kubernetes
- Minikube
- Helm
- Docker
- NGINX
- PostgreSQL
- PowerShell
- Git & GitHub

## Kubernetes Resources

The project includes:

- Deployment
- Service
- Ingress
- ConfigMap
- Secret
- PersistentVolume
- PersistentVolumeClaim
- StatefulSet
- ServiceAccount
- Role
- RoleBinding

## Helm

A Helm chart is available in:

task6-chart/

The Helm deployment includes:

- 2 NGINX replicas
- NodePort Service
- ServiceAccount
- Helm test

## Helm Operations

The following operations were successfully performed:

```text
helm install
helm upgrade
helm history
helm rollback
helm test
helm lint