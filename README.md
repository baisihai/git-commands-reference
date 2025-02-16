# ![alt text](./media/git-logo.png?raw=true) Git Commands Reference

# ![alt text](./media/git.png?raw=true)

## Introduction

Welcome to the Git Commands Reference! 

This reference lists the commonly used commands and is not exhaustive. Where available, the individual command files will provide examples of usage for your reference. Git commands have various options and arguments. It's essential to consult the Git [documentation](https://git-scm.com/docs) for detailed information and usage. Enjoy!

## Commands

- **git init**:
   Initialize a new Git repository in the current directory.

- **git clone [repository URL]**:
   Clone a remote Git repository to your local machine.

- **git add [file]**:
   Stage changes in a file to be included in the next commit.

- **git commit -m "[commit message]"**:
   Record a snapshot of staged changes with a commit message.

- **git status**:
   Display the status of files in the working directory.

- **git diff**:
   Show differences between the working directory and the most recent commit.

- **git log**:
   View commit history with details like commit hashes, authors, and dates.

- **git pull**:
   Fetch remote changes and integrate them into the current branch.

- **git push**:
   Push local commits to a remote repository.

- **git branch**:
   List all branches in the repository.

- **git checkout [branch name]**:
   Switch to a different branch.

- **git merge [branch name]**:
   Merge changes from one branch into the current branch.

- **git remote -v**:
   List remote repositories associated with the current repository.

- **git remote add [remote name] [repository URL]**:
   Add a new remote repository.

- **git remote remove [remote name]**:
   Remove a remote repository from the list.

- **git fetch**:
   Fetch remote changes without merging.

- **git reset [file]**:
   Unstage changes from a file.

- **git reset --hard [commit hash]**:
   Reset the repository to a specific commit, discarding subsequent changes.

- **git rebase [base branch]**:
   Reapply commits from a branch onto another branch.

- **git tag [tag name]**:
   Create a tag at the current commit.

- **git push --tags**:
   Push local tags to the remote repository.

- **git stash**:
   Temporarily save changes that are not ready to be committed.

- **git stash apply**:
   Apply the most recent stash and keep it in the stash list.

- **git stash pop**:
   Apply the most recent stash and remove it from the stash list.

- **git remote show [remote name]**:
   Show information about a remote repository.

- **git remote prune [remote name]**:
   Remove references to remote branches that have been deleted.

- **git config --global user.name "[your name]"**:
   Set your name for commits.

- **git config --global user.email "[your email]"**:
   Set your email for commits.

- **git config --global --list**:
   List your global Git configuration.

- **git log --graph**:
   Display commit history as a graph.

- **git log --oneline**:
   Display compact commit history with abbreviated hashes and messages.

- **git clean -n**:
   Preview untracked files that will be deleted by git clean.

- **git clean -f**:
   Delete untracked files and directories in the working directory.

- **git cherry-pick [commit hash]**:
   Apply a specific commit from another branch onto the current branch.

- **git revert [commit hash]**:
   Create a new commit that undoes changes from a specific commit.

- **git rm [file]**:
   Remove a file from both the working directory and the staging area.

- **git show [commit hash]**:
   Display detailed information about a specific commit.

- **git config --list**:
   List the configuration settings for the current repository.

- **git mv [old file] [new file]**:
   Move or rename a file and stage the change.

- **git blame [file]**:
   Show the commit and author information for each line in a file.

- **git log --author="[author name]"**:
   View commit history by a specific author.

- **git log --since="[date]"**:
   View commit history since a specific date.

- **git log --until="[date]"**:
   View commit history until a specific date.

- **git log -p [file]**:
   Display the commit history for a specific file along with changes.

- **git log --grep="[search term]"**:
   Search for a specific term in commit messages.

- **git commit --amend**:
   Modify the most recent commit with new changes or a new message.

- **git remote rename [old name] [new name]**:
   Rename a remote repository.

- **git remote set-url [remote name] [new URL]**:
   Change the URL of a remote repository.

- **git remote set-head [remote name] [branch name]**:
   Set the default branch for a remote repository.

- **git archive --format=[format] [commit hash] -o [output file]**:
   Create an archive of a specific commit.

## License
The content of this project itself is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International license](https://creativecommons.org/licenses/by-sa/4.0/), and the underlying source code used to format and display that content is licensed under the [MIT license](LICENSE).
