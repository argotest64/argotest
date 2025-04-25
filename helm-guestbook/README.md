
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argotest.git
# cd into the cloned directory
git checkout d1c282a96d6a8962e7aa630c05550a12825d5a7a
helm template . --name-template my-app --include-crds
```