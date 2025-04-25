
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argotest.git
# cd into the cloned directory
git checkout 9a9e922c3e175a79039df3f7c0b588832cded719
helm template . --name-template my-app --include-crds
```