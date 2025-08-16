# Seafile Helm Chart

This Helm chart deploys [Seafile](https://www.seafile.com/) into a Kubernetes cluster.

The chart is published as an OCI artifact in the GitHub Container Registry (GHCR):
📦 `ghcr.io/gera-corp/helm-charts/seafile`

---

## 🚀 Quick Start

### ⚙️ Requirements

- Helm 3.8+ (with OCI support)
- Access to GHCR (if the chart is private)

### 🧩 Install the Chart

```bash
helm install seafile oci://ghcr.io/gera-corp/helm-charts/seafile \
  --version 0.1.1 \
  --namespace seafile \
  --create-namespace \
  --values YOUR-VALUES.yaml
