# Angular - Docker - K8s

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.0.7.

**This is demo project:**

_"How to Deploy Angular application on Kubernetes"_

## Docker

```
docker build -t ivanrozhon/spa-demo:v1 .

docker push ivanrozhon/spa-demo:v1
```

## K8s

https://blog.mayadata.io/openebs/steps-to-deploy-angular-application-on-kubernetes

https://kubernetes.io/docs/concepts/workloads/controllers/deployment/

https://kubernetes.io/docs/concepts/services-networking/service/

```
kubectl apply -f spa-deployment.yaml

kubectl apply -f spa-deployment.yaml

kubectl apply -f spa-loadbalancer.yaml
```

```
kubectl get deployments

kubectl get svc -owide
```

```
minikube start

minikube tunnel
```
