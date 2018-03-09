<img src="https://linuxhint.com/wp-content/uploads/2017/09/kubernetes-375x195.jpg" height="100px" />

---
Welcome !! , this small getting-started guide stands as cheatsheet in order to start using Kubernetes

- [Installation](#install) : install on both linux and windows

<a name="install"/>

## Installation

#### [Minikube](https://github.com/kubernetes/minikube)

```bash
brew install minikube
minikube start
kubectl run hello-minikube --image=k8s.gcr.io/echoserver:1.4 --port=8080
kubectl get pod
```

#### [Kompose](https://kubernetes.io/docs/tools/kompose/user-guide/)

```bash
brew install kompose
```

#### [WebUI](https://kubernetes.io/docs/tools/kompose/user-guide/)

```bash
kubectl create -f https://raw.githubusercontent.com/kubernetes/dashboard/master/src/deploy/recommended/kubernetes-dashboard.yaml
```

## From Docker Compose to Kubernetes


## Raw notes

[Kubectl](https://kubernetes.io/docs/reference/kubectl/overview/)



