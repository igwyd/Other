# Kubectl

### get the current context
`kubectl config current-context`

### get and set context

`kubectl config get-contexts`
`kubectl config use-context <name context>` - that allow you to swich between different kubernetes clusters

### examples
kubectl get pods
kubectl get deploymets
kubectl get services
kubectl get configmaps
kubectl get secrets
kubectl get ingress

### namespaces
kubectl get namespaces
kubectl create namespace test
kubectl get pods -n test
