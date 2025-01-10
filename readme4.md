# touch
- To create blank file (about.html) in current directory
```
touch about.html
```

# checkout
- to revert changes in a file (about.html), i.e., match file content with last commit file content
```
git checkout about.html
```

- to revert changes in all files inthe directory
```
git checkout -f
```

# git log
- to get all information about all commits (what, when and by whom)
```
git log
```

- to see last 5 commits
```
git log -p -2
```
This will show few but detailed commits (what changes made)

# git diff
- to check what changes made in file,
```
git diff
```
This shows all changes made in a file
- pink color text represents: No changes made
- line starting with '-' represents: line removed
- line starting with '+' represents: line added

- to compare stagging area with last commit
```
git diff --staged
```