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

To compare stagging area with last commit
```
git diff --staged
```

# directly commit (Not Recommended)
- to skip adding into stagging area and commit all files directly,
```
git commit -a -m "commit message"
```

# git rm
- To Remove a file (waste.html) not needed, only from stagging area (not hard disk)
```
git rm --cached waste.html
```

- To remove waste file (waste.html), from both stagging area and hard disk
```
git rm waste.html
```