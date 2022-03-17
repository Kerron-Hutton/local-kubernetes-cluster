# Argo CD

[Argo CD](https://argo-cd.readthedocs.io/en/stable) is a declarative, GitOps continuous delivery tool for Kubernetes.

## Why Argo CD?

1. Application definitions, configurations, and environments should be declarative and version controlled.
1. Application deployment and lifecycle management should be automated, auditable, and easy to understand.

## Install Argo CD

```bash
kubectl create namespace argocd
kubectl apply -n argocd -f ./installation-manifest.yaml
```

This will create a new namespace, argocd, where Argo CD services and application resources will live.

## Recommended Resources

- [Getting Started](https://argo-cd.readthedocs.io/en/stable/getting_started/)
- [Declarative Setup](https://argo-cd.readthedocs.io/en/stable/operator-manual/declarative-setup/)
- [Cluster Bootstrapping](https://argo-cd.readthedocs.io/en/stable/operator-manual/cluster-bootstrapping/)
