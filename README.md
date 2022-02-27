# helm-chart-repos

## Add the repo with below command

```
 helm repo add myrepo http://chandrashekarhamse.github.io/helm-chart-repos/
 ```
 
 ## Installing a chart from the repo
 
 ```
helm install my-release myrepo/<chart-name> ## Helm 3
helm install --name my-release myrepo/<chart> ## Helm 2
  ```
  
