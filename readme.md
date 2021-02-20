# My Git Cheatsheet

## Creating a Git Repo

In the folder you want to create a repo, do the following command in terminal

```
git init
```

**Always check that you are not already in a repo by using a git status**

---

## Adding Files to Staging

Staging is files that are being tracked to be committed.

use git status to see which files are untracked(red) or in staging (green)

```
git status
```

three ways to add files to staging

-add one filse at a time `git add <filename>`
-add all files in the repo `git add -A`
-add all files in my current folder with `git add .`

---

## Committing Files to Our Repo

```
git commit -m "adds my first commit -something that describes what changed/action word"
```

**if forget -m you'll end up in vim, to exit type ":wq"**

---

## Looking at our commit history

```
git log
```

```
git log --oneline
```

---

## Working with remotes (enterprise, github, gitlab, bitbucket)

- to add a remote `git remote add <name> <url>`

- to see list of remotes `git remote -v`

  - here you can see all remotes, and their remote names

- to push code `git push <remoteName> <branchName>`

- to see what branch currently on `git branch`

- to remove a remote `git remote rm <remoteName>`
