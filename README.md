# KUBERNETES

## DEPLOYMENT

```$bash
k apply -f mysql-deployment.yaml
k apply -f service-registry-statefulset.yaml
k apply -f config-maps.yaml
k apply -f redis-deployment.yaml
k apply -f config-server-depoyment.yaml
k apply -f cloud-gateway-deployment.yaml
k apply -f product-service-deployment.yaml
k apply -f payment-service-deployment.yaml
k apply -f order-service-deployment.yaml
k apply -f zipkin-deployment.yaml
```

## DELETE

```$bash
k delete -f mysql-deployment.yaml
k delete -f service-registry-statefulset.yaml
k delete -f config-maps.yaml
k delete -f redis-deployment.yaml
k delete -f config-server-depoyment.yaml
k delete -f cloud-gateway-deployment.yaml
k delete -f product-service-deployment.yaml
k delete -f payment-service-deployment.yaml
k delete -f order-service-deployment.yaml
k delete -f zipkin-deployment.yaml
```

## SIMPLE

```$bash
kubectl apply -f k8s
```

```$bash
kubectl delete -f k8s
```
