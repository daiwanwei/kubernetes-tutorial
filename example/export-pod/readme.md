# export-pod
## Table of Contents

 * [專案描述](#專案描述)

## 專案描述
利用service(nodeport)讓pod對外連線 

##Prerequisites
* docker
* minikube
* kubectl

##Getting started

###部署pod 
```bash
$ kubectl create -f pod.yaml 
```

###部署service
```bash
$ kubectl create -f service.yaml
```

###本地端連線到service
```bash
#連線service
$ minikube service echo-service
```

###minikube dashboard
```bash
# 利用minikube監控kubernetes cluster
$ minikube dashboard
```