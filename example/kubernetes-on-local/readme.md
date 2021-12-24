# kubernetes-on-local
## Table of Contents

 * [專案描述](#專案描述)

## 專案描述
本地端建立kebernete cluster

##Prerequisites
* docker

##Getting started

###安裝minikube和kubectl
```bash
# 利用minikube 安裝本地端的kebernete
$ brew install minikube
# 安裝 kubernetes 的 command line
$ curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/darwin/amd64/kubectl"
```

###建立本地kubernetes cluster
```bash
# 利用minikube建立本地端kubernetes cluster(預設建立在docker裡)
$ minikube start
```

###minikube dashboard
```bash
# 利用minikube監控kubernetes cluster
$ minikube dashboard
```

###暫停kubernetes cluster
```bash
$ minikube stop
```

