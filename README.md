# Kubernetes basic commands

1. To install kubectl:
  > brew install kubernetes-cli

2. To ensure the version you installed is sufficiently up-to-date:
  > kubectl version

3. List the available nodes with the command:
  > kubectl get nodes

4. List the current namespaces in a cluster: 
  > kubectl get namespaces

5. kubectl get pods

6. kubectl -n “namespace name” get pods

7. kubectl -n “namespace name” get pods -w

8. List all pods in all namespaces:
> kubectl get pods --all-namespaces  

9. List all pods in the namespace, with more details:
> kubectl get pods -o wide         

10. List all pods in the namespace, including uninitialized ones:
> kubectl get pods --include-uninitialized      

11. List all services in the namespace:
> kubectl get services

12. kubectl get rc

13. You can also get a detailed output of your pod by using the command:
> kubectl describe pods

14. View the deployment with the command:
> kubectl get deployments
