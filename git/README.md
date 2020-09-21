# git

## Settings

```
# configure how line endings are stored in git (for better interoperability)
git config --global core.autocrlf true

# add an alias for a beautiful log
git config --global alias.logex "log --graph --decorate --pretty=oneline --abbrev-commit --all"

# enable single key commands, so we don't have to commit key choices like 'Y' or 'N' with the return key
git config --global interactive.singlekey true
```