1. kubectl apply -f client-pod.yaml
1. kubectl apply -f client-node-port.yaml
1. kubectl get pods
1. kubectl delete -f client-pod.yaml
1. kubectl delete -f client-node-port.yaml
1. kubectl describe pods pod name
1. kubectl describe pods
1. kubectl describe service service_name
1. kubectl descibe service
1. minikube ip
1. minikube service list

kubectl get pods -o wide
eval $(minikube docker-env)
ssh minikube

kubectl set image deployment/client-deployment client=babitabisht/multi-client:v11

kubectl  logs pod_name
kubectl exec -it pod_name bash