# k8s-lab

Kubernetes lab on a kind cluster (1 control-plane + 2 workers): Helm, Gateway API (Envoy Gateway),
NetworkPolicy, StatefulSet, RBAC, GitOps with Argo CD.

- `apps/web` - plain manifests (Deployment, Service, ConfigMap)
- `apps/site` - custom Helm chart
