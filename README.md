# kube-kwatch
For Monitoring Pods Kubernetes 
Note: "Change address webhook mattermost in kwatch-config.yml"

kubectl create namespace kwatch\
kubectl apply -f kwatch-config.yml -n kwatch\
kubectl apply -f kwatch-deployment.yml -n kwatch 
