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

- when `git add -A`, all files (listed in .gitignore) will be ignored by git and not added to stagging area

- to ignore only file (mylogs.log) in root dir, only write `/mylogs.log`
- to ignore all files with extension `.log`, write `*.log`
- to ignore all files in some directory (`ignore`), write `ignore/`

- git ignores empty directories by default