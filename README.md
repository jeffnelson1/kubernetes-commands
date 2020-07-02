# Kubernetes Overview

## Common kubectl commands

| Command
| ---------------
| kubectl version
| kubectl cluster-info
| kubectl get
| kubectl describe
| kubectl apply
| kubectl delete

## Creating objects

This command will apply all manifest files in your current directory to create new objects.
```
kubectl apply -f .
```

This command applies a specific manifest file.
```
kubectl apply -f ./folder/nginx.deployment.yml
```

## Deleting objects

This command will delete your objects if the manfests are in your current directory.

```
kubectl delete -f .
```

This command deletes object from a specific manifest file.
```
kubectl delete -f ./folder/nginx.deployment.yml
```

## Viewing and finding resources

This command will retrieve all resources including your pods, services, deployments, and replica sets.

```
kubectl get all
```

This command will retrieve all pods.

```
kubectl get pods
```

This command will retrieve all services.

```
kubectl get services
```
This command will retrieve all replica sets.

```
kubectl get replicasets
```


