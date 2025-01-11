# Git Branches
In Git, a branch is a new/separate (copy) version of the main repository.

- users can work on copy branch without affecting the main branch

- to create new branch in git,
```
git branch branch_name
```

- we can see all branches using `git branch`, where branch in green text is the current one

- to switch to another branch,
```
git checkout branch_name
```

- now, if we again checkout to other branch, changes will be seen in it. To merge changes into main branch,
