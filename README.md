# Kubernetes Canary Deployment on AWS EKS

Implemented a blue/green deployment strategy using Kubernetes, AWS Load Balancer Controller and weighted traffic routing.

## Stack

- AWS EKS
- Kubernetes
- AWS ALB Controller
- Ingress
- Canary Deployments
- Prometheus
- Grafana

## Features

- Blue/Green deployment
- Weighted traffic split
- Canary rollout strategy
- ALB ingress integration
- Observability dashboards
- Production-style deployment workflow

## Components

- Deployments
- Services
- Ingress
- Canary ingress
- ConfigMaps
- Secrets

## Usage

```bash
kubectl apply -f .
