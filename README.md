# K8S

Comandos:

kubectl create -f deployments/mysql-dp.yml --save-config
kubectl create -f services/mysql-svc.yml --save-config

kubectl create -f deployments/primeiro-dp.yml --save-config
kubectl create -f services/primeiro-svc.yml --save-config

kubectl get all -n development

minikube tunnel
minikube service primeiro-svc
