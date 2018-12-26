# Kubernetes basic commands

To install kubectl:
brew install kubernetes-cli

To ensure the version you installed is sufficiently up-to-date:
kubectl version

kubectl get nodes

kubectl get namespace

kubectl get pods

kubectl -n “namespace name” get pods

kubectl -n “namespace name” get pods -w

kubectl get services

kubectl get rc
