# k8s-dashboard


kubectl apply -f recommended.yaml

kubectl apply -f admin-user.yaml

kubectl apply -f cluster-admin.yaml

kubectl -n kubernetes-dashboard create token admin-user
