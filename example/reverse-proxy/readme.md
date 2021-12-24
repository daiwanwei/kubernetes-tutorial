# reverse-proxy
## Table of Contents

 * [專案描述](#專案描述)

## 專案描述
ingress實作reverse proxy 

##Prerequisites
* docker
* minikube
* kubectl

##Getting started

###部署pod 
```bash
$ kubectl create -f pod.yaml 
```

###部署deployment
```bash
$ kubectl create -f deployment.yaml
```

###部署service
```bash
$ kubectl create -f service.yaml
```

###部署ingress
```bash
$ kubectl create -f ingress.yaml
```

###minikube dashboard
```bash
# 利用minikube監控kubernetes cluster
$ minikube dashboard
```