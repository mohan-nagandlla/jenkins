# CICD 

We will deploy completed setup like building pushing imaegs and deploying the helm


## ENV

the above jenkinsfile can require 5 env to run the pipline

  1.namespace   
  the namespace to deploy the package
  
  2.release     
  helm release name
  
  3.HELM_REPO   
  helm chart repo address
  
  4.chart_name  
  helm package name inside the repo

  5.image_verison
  builded image verion number
