---
geometry: margin=25mm
colorlinks: true
---

# Git notes

These are notes for [git](https://git-scm.com/)

## General commands

### git add

This adds a file or many files to the staging area.

```sh
git add <filename>
```

In the above command, there can be one or more file names.

## Branching command

### git checkout -b

This creates a new branch wherever HEAD is, e.g.:

```sh
git checkout -b feature_branching
```

### git commit

Commits are now going to happen on the newly created branch

### git push

The first time a branch is pushed, it needs to be done explicitly, e.g.:

```sh
git push --set-upstream origin feature_branching
```
