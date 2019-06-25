# Kubernetes manifest
Regroupement des ymal pour Kubernetes.

## Test Ambassador
```
kubectl port-forward ambassador-66b5bc448f-tgwwn 8877
http://34.67.175.179/ambassador/v0/diag/
```

## Routing
```
/ --> Frontend
/cas/ --> Authentication
/ressources/ --> Ressources micro-services
```
