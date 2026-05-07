# Project 02 — Multi-Service App

## What I Built
- Frontend (Nginx) on Worker1
- Backend (http-echo API) on Worker2
- Internal DNS communication via ClusterIP
- NodeSelector for pod placement

## Concepts Learned
- ClusterIP vs NodePort
- K8s Internal DNS (CoreDNS)
- NodeSelector
- Resource Limits
- Environment Variables
- Namespace isolation (project-02)

## Access
- Frontend: http://34.197.198.59:30081

## Commands
```
kubectl get all -n project-02
kubectl get pods -n project-02 -o wide
kubectl run curl-test --image=curlimages/curl -n project-02 --rm -it --restart=Never -- curl http://backend-svc
```
