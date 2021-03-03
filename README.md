# git-delete-merged-branches

Git utility script to delete merged local branches.

# Installation

```
curl -O https://raw.githubusercontent.com/kyanny/git-delete-merged-branches/master/git-delete-merged-branches
chmod +x git-delete-merged-branches
install git-delete-merged-branches /usr/local/bin
```

# Git aliases

```
git config --global --add alias.fp '!git fetch -p && git-delete-merged-branches'
git config --global --add alias.pp '!git pull -p && git-delete-merged-branches'
```
