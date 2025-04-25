
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argotest.git
# cd into the cloned directory
git checkout cac5b8c8231f7e64ea15adce7260ae48fad226ec
helm template . --name-template my-app --include-crds
```