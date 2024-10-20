##  All Git Related Commands with description #######

Entry-Level Git Commands

git init
Initializes a new Git repository in your project.

git clone [url]
Clones an existing repository from a remote server.

git status
Shows the status of changes as untracked, modified, or staged.

git add [file]
Adds a file to the staging area (or git add . to add all files).

git commit -m "[message]"
Records changes to the repository with a message.

git push [remote] [branch]
Pushes changes to a remote repository (e.g., origin master).

git pull [remote] [branch]
Fetches and merges changes from a remote repository.

git branch
Lists all branches in the repository.

git checkout [branch]
Switches to a different branch.

git log
Shows the commit history for the current branch.




Intermediate-Level Git Commands
git remote -v
Displays the remote repositories connected to your project.

git merge [branch]
Merges the specified branch into the current branch.

git stash
Temporarily stores changes that are not ready to be committed.

git stash pop
Applies stashed changes back into the working directory.

git fetch [remote]
Downloads objects and references from another repository.

git diff
Shows differences between files in the working directory, staged changes, or between branches.

git reset [file]
Removes the file from the staging area, but keeps changes in the working directory.

git reset --hard [commit]
Resets the index and working directory to the specified commit, discarding all changes.

git rebase [branch]
Reapplies commits on top of another base branch.

git tag [tag-name] [commit-id]
Creates a tag at a specific commit for versioning.




Advanced-Level Git Commands
git cherry-pick [commit]
Applies a specific commit from one branch to another.

git bisect
Helps find the commit that introduced a bug by binary search between two commits.

git reflog
Shows the history of changes to the tip of branches and other references.

git blame [file]
Shows the last modification for each line in a file, useful for tracking changes.

git submodule add [url]
Adds a submodule to your repository (useful for monorepos).

git filter-branch
Rewrites Git history by filtering branches with specific criteria (use cautiously).

git worktree add [branch] [directory]
Creates a new working tree attached to an existing branch.

git clean -f
Removes untracked files from the working directory.

git revert [commit]
Reverts a specific commit by creating a new one that undoes the changes.

git bundle
Creates a bundle of the repository to share offline.

git fsck
Verifies the integrity of the Git file system.

git hook
Configures custom scripts to run at certain stages of the Git workflow (pre-commit, post-commit, etc.).

Collaboration and Workflow Commands
git cherry -v
Shows commits that exist on the current branch but not on the upstream branch.

git shortlog
Summarizes git log history, showing author names and commit counts.

git describe
Provides human-readable descriptions for commits using tags.

git apply [patch-file]
Applies a patch to the working directory or staging area.

git archive [branch]
Creates a tar or zip archive of the repository at a specific point in time.

git blame -L [line-range]
Shows who modified specific lines of a file.
