# Github Remote Repository
Remote repositories are versions of your project that are hosted on the Internet or network somewhere (like Github).

- A remote URL is Git's fancy way of saying "the place where your code is stored." That URL could be your repository on GitHub, or another user's fork, or even on a completely different server.

- To add git remote URL (here github git-tutorial repository url),
```
git remote add origin https://github.com/anmolkhurana490/Git-Tutorial.git
```
it means "add given remote url into git and name it as origin"

- now we can check git remote name, `git remote`
- to check remote url, `git remote -v`

- to push out code from branch (main) to remote (origin),
```
git push origin main
```