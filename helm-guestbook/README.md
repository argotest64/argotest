
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone git@github.com:argotest64/argotest.git
# cd into the cloned directory
git checkout 4ca58a8286affdb260fdf721af52a1a76ad2b7ff
helm template . --name-template my-app --include-crds
```