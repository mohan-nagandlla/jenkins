# Kubernets cluster accessing

We can able to access the resources of Kubernets by rbac 

## admin rbac

kubectl create clusterrolebinding jenkins-admin-binding --clusterrole=cluster-admin --serviceaccount=[jenkins namespace]:default

## ENV

the above jenkinsfile can require 4 env to run the pipline

  1.namespace   
  the namespace to deploy the package
  
  2.release     
  helm release name
  
  3.HELM_REPO   
  helm chart repo address
  
  4.chart_name  
  helm package name inside the repo
