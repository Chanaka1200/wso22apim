# wso22apim

1. install helm latest version
2. install kubectl latest version
3. install minikube latest
4. install docker
5. docker login --username=wso2username --password=wso2password
6. minkube start --driver=docker
7. minikube addons enable ingress
   https://kubernetes.io/docs/tasks/access-application-cluster/ingress-minikube/
8. eval $(minikube docker-env)
9. skaffold dev