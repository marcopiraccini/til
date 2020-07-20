# How to mirror a git repo in another 

It's possible to export and import using `git fast-export` and `git fast-import`. 
For instance, this will mirror a repository into another: 

```
git fast-export --all | (cd /empty/repository && git fast-import)
```

Using `fast-export` it's also a good wayfo sharing a repo when cloning is not possible (e.g. the repo is private). If so, simply: 

```
git init
git fast-import < ../exported.git
```
