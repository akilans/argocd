# Argocd

### Installation

- kubectl create namespace argocd
- kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml
- kubectl edit svc -n argocd argocd-server - Change it to NodePort type
- Access the UI. Login with admin and default pasword will be pod name

###
