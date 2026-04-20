kubectl cluster-info

kubectl create deployment myapp --image=nginx

kubectl get deployment

kubectl scale deployment myapp --replicas=2

kubectl get pods

kubectl expose deployment myapp --type=NodePort --port=80

kubectl get services

kubectl create deployment myapp --image=nginx --dry-run=client -o yaml > deploy.yaml

kubectl apply -f deploy.yaml

kubectl get all

kubectl get deployment myapp -o yaml

kubectl delete deployment myapp

kubectl delete service myapp
