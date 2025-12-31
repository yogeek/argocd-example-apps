# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/yogeek/argocd-example-apps
# cd into the cloned directory
git checkout b214a6404f2859ad4826ea78542f6eb6f9b195d2
helm template . --name-template guestbook-val --include-crds
```
