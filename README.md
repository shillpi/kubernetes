# Kubernetes basic commands

To install kubectl:
> brew install kubernetes-cli

To ensure the version you installed is sufficiently up-to-date:
> kubectl version

List the available nodes with the command:
> kubectl get nodes

kubectl get namespace

kubectl get pods

kubectl -n “namespace name” get pods

kubectl -n “namespace name” get pods -w

List all pods in all namespaces:
> kubectl get pods --all-namespaces             

List all services in the namespace:
> kubectl get services

kubectl get rc

You can also get a detailed output of your pod by using the command:
> kubectl describe pods

View the deployment with the command:
> kubectl get deployments
