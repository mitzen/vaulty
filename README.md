# vaulty

K8s that automatically mount and refresh config / secrets in kubernetes cluster for your applications. 

Application often rely on keys/secret from external services like Azure keyvaut or vault from Hashicorp. 

this operator automatically syncs and update configuration chnages to k8s cluster to ensure secrets are constantly updated. 
It also supports certificates. 

