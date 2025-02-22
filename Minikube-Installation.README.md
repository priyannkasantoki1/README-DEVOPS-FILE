# Install Minikube On Linux

## Set up the repository

```bash
   curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-arm64
```

## Install Minikube

```bash
  sudo install minikube-linux-arm64 /usr/local/bin/minikube && rm minikube-linux-arm64
```

## Run command

```bash
sudo minikube start --driver=docker
```
## Interact with your cluster

```bash
  kubectl get po -A
```
## Manage your cluster

```bash
sudo  minikube pause
```
```bash
sudo minikube unpause
```
```bash 
sudo minikube stop
```
##  Delete all of the minikube clusters:

```bash
sudo minikube delete --all
```

## Authors

- [@Priyannka-Santoki](https://www.github.com/priyannkasantoki1)
