# What is this crap
Just a demo setup of overide of the standard garana config

Choices for deployment

1. It has vanilla k8s config in the root folder
2. kube-prometheus using the prometheus operator and postgres in the kube-prometheus folder

The second setup has postgres for storage which the first setup does not have.

# How do i apply this
*From the root folder*
```
kubectl apply -k .
```


# Deploy setup with kube-prometheus
```
cd kube-prometheus
kubectl apply -k .
```