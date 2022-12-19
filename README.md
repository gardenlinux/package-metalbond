# Metalbond package

Upstream is in Github https://github.com/onmetal/metalbond

## How to Release
Like every other Garden Linux package, the deploy build pipeline is triggered when a new git tag is pushed.

You can create a git tag [here](https://gitlab.com/gardenlinux/gardenlinux-package-metalbond/-/tags), or via cli

```
git clone git@gitlab.com:gardenlinux/gardenlinux-package-metalbond.git
cd gardenlinux-package-metalbond
# Adapt the version
TAG_NAME="gardenlinux/0.3.0-0gardenlinux1"
git tag $TAG_NAME
git push origin $TAG_NAME
```
