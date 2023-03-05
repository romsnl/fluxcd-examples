# fluxcd-examples

Fluxcd gitops repository example used for demo/testing purpose.

## Structure

> apps-dev

apps-dev regroup apps used on our dev clusters

```txt
❯ flux tree ks apps-dev   
Kustomization/flux-system/apps-dev
├── Namespace/gohead
├── Service/gohead/gohead
└── Deployment/gohead/gohead
```
