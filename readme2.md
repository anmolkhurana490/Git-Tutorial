# Initialise Project

- Initialse project using command
```
git init
```

- When the project is initialised, it makes .git/ directory (hidden). You can see this directory using
```
las -lart
```

# git status
- Initially, all files are untracked. You can all files status using
```
git status
```

# git add
- To add file (index.html) into stagging area
```
git add index.html
```

- to add all files into stagging area
```
git add -A
```

# git commit
- To start tracking all stagged files,
```
git commit
```

This opens VIM editor, write commit message (like "Initial Commit") then save quit file.
Now, all staged files are commited (git tracks their changes).

# touch
- To create blank file (about.html) in current directory
```
touch about.html
```