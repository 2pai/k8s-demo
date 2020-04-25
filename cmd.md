## setup virtualizer
kubectl proxy -w=k8s-visualizer/src/
<!-- kubectl proxy --www=gcp-live-k8s-visualizer --www-prefix=/my-mountpoint/ --api-prefix=/api -->
## Pods

kubectl apply -f pods/nginx.yaml   
kubectl apply -f service/nginx-service.yaml   

## Replicaset
kubectl apply -f replicaset/demo-replicaset.yaml   

# deployment
kubectl apply -f deployment/depolyment.yaml
kubectl apply -f service/demo-service.yaml   
