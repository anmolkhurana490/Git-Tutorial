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

- to get status of files (in summarized way)
```
git status -s
```
This shows M's (modified) in 2 blocks
- first block (having green M) represents Modified in Stagging area
- second block (having red M) represents Modified in Working directory

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

- we can directly commit files without openig VIM editor
```
git commit -m "commit message"
```