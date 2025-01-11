# git ignore
- make a .gitignore file in current directory, uisng
```
touch .gitignore
```

- write all files names (dir name not needed, as git will check by itself) in .gitignore file,
for example
```
mylogs.log
```

- when ```git add -A```, all files (listed in .gitignore) will be ignored by git and not added to stagging area