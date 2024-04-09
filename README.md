# git-demo
This repository is used to demonstrate git features

# Basic terms
**Repository (Repo):**\
A directory or storage space where files, history and branches are stored.

**Branch:**\
A separate line of development.

**Commit**:\
A record of changes to one or more files along with a message describing the changes.

**Merge:**\
The process of combining changes from a branch into another.

**Pull Request (PR):**\
A request to merge changes from one branch to another. It allows collaborators to review and discuss proposed changes before merging.

**Remote:**\
A repository hosted elsewhere than the local/work machine (e.g. GitHub, Azure DevOps).

**Origin:**\
A shorthand name for the remote repository that a project was originally cloned from.

**Push:**\
Refers to sending your committed changes to a remote repository (origin), making it accessible to others.

**Pull:**\
Refers to fetching and merging changes from a remote repository (origin) into your local branch.

**Clone:**\
Cloning a remote branch copies/downloads that branch into the local system.

**Checkout:**\
Checking out a branch switches between branches already on the local system.

**Staging:**\
Staging is where you prepare and organise changes before committing them to the repository.

**Conflict:**\
A conflict occurs when Git cannot automatically resolve some differences between branches when attempting to merge those branches.

# Making Changes
1. File changes
2. Stage changes
3. Commit changes (to local branch)
4. Push commits (to remote/origin branch)

# Undoing Changes
1. **Discard changes:** Changes that have not been committed can be discarded
2. **Unstage changes:** Changes that have been staged can be unstaged (and discarded)
3. **Revert commit:** Reverting a commit will create a new commit that reverses the changes made in the selected commit.
4. **Reset branch head:** A branch's head can be moved back to a previous commit. Commits *after* the head will not be pushed to the remote branch.
