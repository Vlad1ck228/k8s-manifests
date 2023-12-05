# k8s-manifests FOR GRAFANA

kubectl apply -f prometheus.yaml

kubectl apply -f grafana.yaml

kubectl apply -f node-exporter.yaml

kubectl apply -f prometheus-configmap.yaml

minikube tunnel

kubectl get svc

kubectl rollout restart deployment prometheus-deployment # to restart prometheus, after changes in prometheus-configmap.yaml

GRAFANA AND PROMETHEUS run on 80 ports, NODE-EXPORTER on 9100
