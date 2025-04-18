---
title: Branch and Remote Commands
date: April 17, 2025
---

Rename a local branch.

```
git branch -m oldname newname
```

Pull down a remote branch named bugfix and automatically switch to that branch.

```
git checkout bugfix
```

Push local branch named bugfix to remote named origin.

```
git push origin bugfix
```

Remove local references to remote branches that have been deleted.

```
git remote prune origin
```

Change the URL associated with the remote repository named origin.

```
git remote set-url origin https://github.com/wigging/macdevs.git
```