# demo-app GitOps repo

ArgoCD-managed demo application that reads secrets from HashiCorp Vault
via the Vault Agent Injector.

## Structure

- `charts/demo-app/` — the Helm chart
- `argocd/demo-app-application.yaml` — the ArgoCD Application CR

## Deploy

```bash
kubectl apply -f argocd/demo-app-application.yaml
