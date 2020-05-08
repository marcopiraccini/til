# How to recover after an accidental `git reset --hard` 

Use `git reflog` to get the reference and then reset hard, e.g.:

```
git reset --hard HEAD@{5}

```

See: https://git-scm.com/docs/git-reflog



