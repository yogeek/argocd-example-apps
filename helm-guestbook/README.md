# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/yogeek/argocd-example-apps
# cd into the cloned directory
git checkout 09bfaefef37474c69731bf0733a3e3b139df7789
helm template . --name-template guestbook-prod --include-crds
```
