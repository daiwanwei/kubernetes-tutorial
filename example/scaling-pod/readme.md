# scaling-pod
## Table of Contents

 * [專案描述](#專案描述)

## 專案描述
scaling pod

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

###minikube dashboard
```bash
# 利用minikube監控kubernetes cluster
$ minikube dashboard
```