
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argotest.git
# cd into the cloned directory
git checkout 0d6f4f434a649061437679792b550264e2ca4eaf
helm template . --name-template my-app --include-crds
```