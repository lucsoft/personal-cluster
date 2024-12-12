# HmSYS Cluster

## Tools

- talhelper
- sops

## Pkl

### Adding new CRDs

```bash
pkl eval package://pkg.pkl-lang.org/pkl-pantry/k8s.contrib.crd@1.0.13#/generate.pkl \
  -m . \
  -p source="https://raw.githubusercontent.com/argoproj/argo-cd/v2.7.2/manifests/install.yaml"
```
