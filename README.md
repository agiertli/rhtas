# Usage

1) Fix [argo-apps/rhtas-install/values.yaml](argo-apps/rhtas-install/values.yaml) so it fits your cluster
2) Using `oc` cli , log into the OpenShift cluster as cluster-admin
3) 

```bash
cd install/
./install.sh -p password1!
```

4) Verify installation using [verify-installation](verify-installation/README.md) folder