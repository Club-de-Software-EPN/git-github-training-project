# How to modify branches
## Introduction
Once we've created our branches we always need to do some modifications. For instance, we already finish a stable version of our product. So, we'll need to remove the hotfix branch or maybe develop branch. That's why the next commands will help with this.

## Changing between branches
We always working in differents area. That's why we always be changing the branch we are working. This command allows you change beetwen branches.
```
git checkout "name of the branch"
```

## Rename a branch
If you want to change the name because it's wrong or it has been modified by the documentation. Here are the command.
```
git branch -m "old name" "new name"
```

## Remove a branch
These commands allows you to remove a branch. And it depends the situation.
- Branch without changes or empty
```
git branch -d "name of the branch"
```
- Branch with changes, the command ignores the changes.
```
git branch -D "name of the branch"
```

## View differences beetwen branches
If we have modified our branches, means that they had to have differences. We can use the next command in order to view these changes.
```
git diff "branch1" "branch2"
``` 
## Git log for branches
Ir order to view how our branches are. We can use a git log using this.
```
git log --oneline --graph --all
``` 
![git log for branches](https://mackyle.github.io/git-log-compact/image1.gif)

