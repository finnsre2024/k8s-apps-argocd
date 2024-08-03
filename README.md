## Deploy applications on kubernetes with argocd
This is a sanitized version of a previous deployment I did, which involved deploying microservices to Kubernetes in conjunction with ArgoCD for CI/CD. Please review it.



kubectl create ns argocd
kubectl apply -n argocd -f ./argocd-installation/install.yaml
kubectl apply -f ./argocd-installation/argocd-ingress.yaml

kubectl get secret argocd-initial-admin-secret -n argocd -o yaml
[Text.encoding]::Utf8.GetString([Convert]::FromBase64String('MDhhUGhoOWl4cjkzOG9Paw=='))
Argo CD password: ulSoG6OXpqA0AVN9


[Text.encoding]::Utf8.GetString([Convert]::FromBase64String('WDRXcjNzS1l1SThPaXZTeA=='))
