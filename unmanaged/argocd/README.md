> https://github.com/argoproj/argo-helm/tree/main/charts/argo-cd#installing-the-chart

- helm repo add argo https://argoproj.github.io/argo-helm
- helm repo update
- helm upgrade --install argocd argo/argo-cd --namespace argocd --create-namespace --values values.yaml