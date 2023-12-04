# k8s-manifests FOR GRAFANA
kubectl apply -f prometheus.yaml
kubectl apply -f grafana.yaml
kubectl apply -f node-exporter.yaml

minikube tunnel

kubectl get svc -o wide
