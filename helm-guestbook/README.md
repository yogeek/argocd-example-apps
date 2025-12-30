# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/yogeek/argocd-example-apps
# cd into the cloned directory
git checkout 53ced3628a77b81fbdb551743391041548210b77
helm template . --name-template guestbook-prod --include-crds
```
