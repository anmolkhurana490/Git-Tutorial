# Git Branches
In Git, a branch is a new/separate (copy) version of the main repository.

- users can work on copy branch without affecting the main branch

- to create new branch (feature1) in git,
```
git branch feature1
```

- we can see all branches using `git branch`, where branch in green text is the current one

- to switch to another branch (feature1),
```
git checkout feature1
```

- now, if we again checkout to feature1 branch, changes will be seen in it.
- To merge changes into main branch, write command from main branch
```
git merge feature1
```

- to directly create new branch (flaskIntegration) and checkout to it,
```
git checkout -b flaskIntegration
```