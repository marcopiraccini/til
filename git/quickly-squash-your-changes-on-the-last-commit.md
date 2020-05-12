# Quickly squash your changes on the last commit 

Instead of creating a commit and then squash, just stage your changes an then:

```
git commit --amend --no-edit
```

This will amend your last commit with staged stuff, maintaining the comment. 
