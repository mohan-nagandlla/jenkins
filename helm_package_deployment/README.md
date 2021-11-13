# Kubernets cluster accessing

We can able to access the resources of Kubernets by rbac 

## admin rbac

kubectl create clusterrolebinding jenkins-admin-binding --clusterrole=cluster-admin --serviceaccount=[jenkins namespace]:default

## privilized rbac

the file is available in the name of rbac.yaml
