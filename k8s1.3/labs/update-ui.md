
```
kubectl delete deployments kubernetes-dashboard --namespace kube-system
kubectl delete svc kubernetes-dashboard --namespace kube-system
```

```
kubectl create -f https://rawgit.com/kubernetes/dashboard/master/src/deploy/kubernetes-dashboard.yaml
```

```
kubectl config view | grep "server:\|password:"
```
