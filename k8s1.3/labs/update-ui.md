
kubectl delete deployments kubernetes-dashboard --namespace kube-s
ystem
kubectl delete svc kubernetes-dashboard --namespace kube-s
ystem

kubectl create -f https://rawgit.com/kubernetes/dashboard/master/src/dep
loy/kubernetes-dashboard.yaml

kubectl config view
