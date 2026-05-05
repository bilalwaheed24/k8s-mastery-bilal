# Project 01 — Hello Kubernetes

## Cluster Info
- Master: 54.164.24.20
- Worker1: 34.197.198.59  
- Worker2: 44.219.128.219
- Region: us-east-1

## What I Built
- NGINX app on K8s
- 3 replicas + 1 standalone pod
- NodePort service (port 30080)
- Namespace: project-01

## Concepts Learned
- Pod, Deployment, ReplicaSet
- NodePort Service
- Self-healing
- Namespace isolation
- Labels & Selectors

## Commands
```
kubectl apply -f pod.yaml
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
kubectl get all -n project-01
```
