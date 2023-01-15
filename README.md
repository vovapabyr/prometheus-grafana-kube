## Kubernetes sample
### Prometheus & Grafana

Kubernetes folder structure:
```
├── kube
    └── grafana-deployment.yaml
    └── grafana-secret.yaml
    └── grafana-service.yaml
    └── prom-data-persistentvolumeclaim.yaml
    └── prometheus-deployment.yaml
    └── prometheus-service.yaml
```

## Deploy with kubectl

Go to 'kube' folder and run ```kubectl apply -f .```

## Expected result
![prometheus-grafana-cluster-info](https://user-images.githubusercontent.com/25819135/212537209-39e391fa-be44-4441-872f-0f321e6082fd.png)
