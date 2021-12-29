# helm-deploy
## Table of Contents

 * [專案描述](#專案描述)

## 專案描述
本地端helm部署

##Prerequisites
* docker
* minikube
* kubectl
* helm

##Getting started

###helm部署
```bash
$  cd path-to-dir/helm-deploy
$  helm install helm-demo .
```

###helm更新
```bash
$  cd path-to-dir/helm-deploy
$  helm upgrade helm-demo .
```

###helm移除
```bash
$  cd path-to-dir/helm-deploy
$  helm delete helm-demo 
```

###minikube dashboard
```bash
# 利用minikube監控kubernetes cluster
$ minikube dashboard
```
