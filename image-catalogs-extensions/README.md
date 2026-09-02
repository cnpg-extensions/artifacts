[![CNPG Extensions](../logo/cnpg-extensions.png)](https://github.com/cnpg-extensions/)

# Extension Image Catalogs

This directory is reserved for the official `ClusterImageCatalog` manifests
maintained by [CNPG Extensions](https://github.com/cnpg-extensions/) for
PostgreSQL extension images that can be used with
[CloudNativePG](https://cloudnative-pg.io/).

No catalogs are published yet. The directory and its Kustomize entry point are
intentionally empty until the first catalogs are available.

When catalogs are added, individual manifests can be installed from this
directory, or all catalogs can be installed with:

```sh
kubectl apply -k \
  https://github.com/cnpg-extensions/artifacts/image-catalogs-extensions?ref=main
```
