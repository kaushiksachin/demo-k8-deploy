# demo-K8-deploy

Commands in sequence:

```kubectl create -f demo/redis-master-controller.yaml```

```kubectl create -f demo/redis-master-service.yaml```

```kubectl create -f demo/redis-slave-controller.yaml```

```kubectl create -f demo/redis-slave-service.yaml```

```kubectl create -f demo/frontend-controller.yaml```

```kubectl create -f demo/frontend-service.yaml```
