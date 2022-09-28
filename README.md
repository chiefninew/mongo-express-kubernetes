# mongo-express-kubernetes

# Technologies
- [Docker](https://www.docker.com/)
- Kubernetes

# Prerequisite
- [Docker Desktop](https://www.docker.com/products/docker-desktop/)
- Kubernetes

# How to run?
```
kubectl apply -f pv.yaml
kubectl apply -f pvc.yaml
kubectl apply -f secrets.yaml
kubectl apply -f mongodb.yaml
kubectl apply -f configMap.yaml
kubectl apply -f mongo-express.yaml
kubectl apply -f ingress.yaml
```

#### Add mongo-express.example to your host file

