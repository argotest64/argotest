
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argotest.git
# cd into the cloned directory
git checkout 6b33f1f94e4b9cf584feadf4e43fcdc3f04e6b35
helm template . --name-template my-app --include-crds
```