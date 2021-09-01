# 2021-09-01: NYR Git Workshop

- `git init`: initialize git repository
- `git status': display current repo ststus
- `git add <FILE>`: adds <FILE> to staging area
- `git commit`: opens text editor to commit contents of staging area
  - `-m "<message>"`: use <message> as commit message without opening editor
- `git log`: shows repo history
  - `--oneline`: each commit is shown as a single line
- `git diff [HEAD~#/hash#]`: display changes between commits and current state
- `git restore`:
- `git checkout <HASH> <FILE>`: revert <FILE> to the version in <HASH>
  - `git checkout <HASH>`: move HEAD to <HASH> (detached HEAD state)
  - `git switch main`: reattach HEAD to latest commit of main branch

## REMOTES

- `git remote add <NAME> <URL>`: add remote named <NAME> using <URL>
  - `git remote add <NAME> <BRANCH>':
- `git remote -v:` display configured remotes
- `git push <REMOTE> <BRANCH>`: push local changes in <BRANCH> to <REMOTE>
- `git pull <REMOTE> <BRANCH>`: pull <BRANCH> changes from <REMOTE> to local  
- Conflicts may happen during push/pull sync  

## BRANCHES

- `git branch <NAME>`: create branch at HEAD
- `git branch -a`: list all branches
- `git switch <BRANCH>`: move head to <BRANCH>
  - `git checkout <BRANCH>`: alternate syntax (older)
 