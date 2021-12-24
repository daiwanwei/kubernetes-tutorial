# deploy-to-kubernetes
## Table of Contents

 * [專案描述](#專案描述)

## 專案描述
部署一個專案至kubernetes

##Prerequisites
* docker
* minikube
* kubectl

##Getting started

###部署echoserver 至 kubernetes
```bash
$ kubectl create -f pod.yaml 
```

###將本地端的port mapping到 kubernetes
```bash
$ kubectl port-forward echoserver-pod 8080:8080 
```

###minikube dashboard
```bash
# 利用minikube監控kubernetes cluster
$ minikube dashboard
```
