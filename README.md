# Overview

This repository install default instance of [Red Hat Trusted Artifact Signer](https://developers.redhat.com/blog/2023/11/15/announcing-red-hat-trusted-artifact-signer-rhtas-tech-preview) with integrated RH-SSO (used as OIDC Provider for Fulcio) on OpenShift (tested with 4.14). The installation is backed by ArgoCD.
[Following users](argo-apps/keycloak-install/user.yaml) are available in RH-SSO.

Follow

# Usage

1) Fix [argo-apps/rhtas-install/values.yaml](argo-apps/rhtas-install/values.yaml) so it fits your cluster
2) Using `oc` cli , log into the OpenShift cluster as cluster-admin
3) 

```bash
cd install/
./install.sh -p password1!
```

4) Verify installation using [verify-installation](verify-installation/README.md) folder