## Apply cert manager

kubectl apply -f argo-apps/cert-manager.yaml -n argocd

## Validate the above

kubectl get pods -n cert-manager
kubectl get crds | grep cert-manager


