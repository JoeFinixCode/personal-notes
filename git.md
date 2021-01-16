# My Git and Github notes

## How to add all files to the staging area

```console
git add .
```

## How to add specific file to the staging area

```console
git add index.html
```

## How to check the staged/cached files in the staging area

```console
git status
```

## How to removed staged files or cached files from git add

```console
git rm --cached -r .
```

## How to commit the staged files

```console
git commit -m "commit message"
```

## How to check branch name

```console
git branch
```

## How to change branch name

```console
git branch -m <currentBranch> <newBranch>
```

## How to show git branches with their commits

```console
git show-branch
```

## How to show git branches from local and remote repo

```console
git branch -a
```

## How to show git branches from remote repo

```console
git branch -r
```

## How to show git branches from remote repo with commits

```console
git show-branch -r
```

## How to show git branches from local repo with commits

```console
git show-branch -all
```

## How to clone git repo main branch

```console
git clone <repo link>
```

## How to create another branch

```console
git branch <new-branch-name>
```

## How to switch to another branch

```console
git checkout <branch-name-you-wanna-switch>
```

## How to clone a specific branch

```console
git clone --branch <branch-name> <remote-repo-url>
```

or

```console
git clone -b <branch-name> <remote-repo-url>
```

## How to connect to remote repo

> origin is a remote name and you can name it anything you want. But by convention we name it origin.

```console
git remote add origin <repo link>
```

# How to merge a branch

```console
git merge <the-branch-name-that-you-want-to-merge-from-your-current-branch>
```
