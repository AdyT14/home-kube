# How to add kubernetes dashboard:

## Steps
### 1) Adding kubernetes dashboard
- Adding the repo: `helm repo add kubernetes-dashboard https://kubernetes.github.io/dashboard/`
- `helm upgrade --install kubernetes-dashboard kubernetes-dashboard/kubernetes-dashboard --create-namespace --namespace kubernetes-dashboard`

### 2) Creating an admin user
`kubectl apply -f dashboard-adminuser.yaml`


### 4)




## Useful links:
- Github page: https://github.com/kubernetes/dashboard/
- 