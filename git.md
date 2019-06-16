# Git

## Commands

### clone

- `git clone myrepository.git` : Clones the repositoriy `myrepository.git`.

### add

- `git add my-file` : Adds my-file.
- `git add .` : Adds all items.

### commit

- `git commit -m "My commit message."` : Commits with the message `My commit message.`.

### push

- `git push` : Pushes local commits to the remote.
- `git push -u origin feature/branch` : Pushes commits of the branch `feature/branch` and sets it as upstream.

### checkout

- `git checkout feature/branch` : Switches to branch `feature/branch`.
- `git checkout -b feature/new-branch` : Creates a new branch `feature/new-branch` and switches to it.

### cherry-pick

- `git cherry-pick abcd1234` : Cherry-picks commit `abcd1234`.

### reset

- `git reset HEAD~1` : Brings back changes from the last commit to the stage.
- `git reset --hard origin/feature/branch` : Restores the branch `feature/branch` from the remote `origin` in the local repository.

### rebase

- `git rebase master` : Rebases the current branch from the `master` branch.
- `git rebase -i HEAD~3` : Interactive rebase of the last 3 commits.

### clean

- `git clean -fdx` : Deletes all untracked files.