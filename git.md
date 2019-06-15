# Git

## Commands

### clone

Clones a repository.

- `git clone myrepository.git` : Clones the repositoriy `myrepository.git`.

### add

Adds items to the stage.

- `git add my-file` : Adds my-file.
- `git add .` : Adds all items.

### commit

Commits the items to the source control.

- `git commit -m "My commit message."` : Commits with the message `My commit message.`.

### push

Pushes the items to the remote.

- `git push` : Pushes local commits to the remote.
- `git push -u origin feature/branch` : Pushes commits of the branch `feature/branch` and sets it as upstream.

### checkout

Switches to another branch.

- `git checkout feature/branch` : Switches to branch `feature/branch`.
- `git checkout -b feature/new-branch` : Creates a new branch `feature/new-branch` and switches to it.

### cherry-pick

Adds a commit to the branch.

- `git cherry-pick abcd1234` : Cherry-picks commit `abcd1234`.