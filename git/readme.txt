how to config local directory to remote repositary ?

    sudo yum install git -y
    
    git --version

    git init 

    git add < . or specific file name>

    git commit -m "any thing you remember"

    git bramch -M <bramch name>

    git remote add origin <url>

    git push -u origin <branch name>





how to clone remote repo in local mashion ?  git clone <url of repo>

how to pull changes from remote repo ? git pull origin <branch name>

how to fetch repo to local mashion ? git fetch

how to merge ? git merge <branch name>

how compaire changes ? git diff

how to view commit history ? git log

how to check branchs ? git branch

how to change branch ? git checkout <branch name>

how to creat a branch ? git branch <branch name>

how to list of remote repos ? git remote -v

how to remove remote repo ? git remote remove <name or url>




Remote Repository Management:

git remote show <remote>: Displays detailed information about a remote repository.
git remote rename <old_name> <new_name>: Renames a remote.
git remote set-url <remote> <new_url>: Changes the URL of an existing remote.




Conflict Resolution:

git mergetool: Launches a visual merge tool to help resolve conflicts.
git diff --base <file>: Shows the original, unmerged version of a conflicted file.
git add <file>: Marks a conflicted file as resolved after manual conflict resolution.
git rm <file>: Removes a conflicted file.




Branch Deletion:

git branch -d <branch_name>: Deletes a local branch (use -d for safe deletion).
git branch -D <branch_name>: Forcefully deletes a local branch.
git push <remote> --delete <branch_name>: Deletes a remote branch.




Ignoring Files:

Create a .gitignore file in your repository and list file patterns to be ignored. For example:

bash
Copy code
# Ignore build artifacts
build/
# Ignore log files
*.log




Show Commit Details:

git show <commit>: Displays detailed information about a specific commit.
git log --oneline --graph --all: Shows a compact graph of all commits in your repository.



Cherry-Picking:

git cherry-pick <commit>: Applies the changes introduced by a specific commit to the current branch.




Interactive Add:

git add -p: Interactively stage changes from your working directory, allowing you to review and stage specific changes within files.




Git Bisect:

git bisect start: Initiates a binary search for a specific commit where a bug was introduced.
git bisect bad: Marks the current commit as bad (contains the bug).
git bisect good <commit>: Marks a known good commit.
git bisect reset: Ends the bisect session.



Revert Multiple Commits:

git revert -n <commit1> <commit2> ... <commitN>: Reverts multiple commits in a single commit.



Git Worktree:

git worktree add <path> <branch>: Creates a new working directory linked to a specific branch.
git worktree remove <path>: Removes a linked working directory.




Stash Operations:

git stash save "message": Stashes changes with a descriptive message.
git stash list: Lists all stashes.
git stash apply <stash>: Applies a specific stash.
git stash drop <stash>: Deletes a specific stash.




Changing Commit History:

git rebase -i HEAD~<N>: Interactively rebase the last N commits.
git commit --amend: Amend the last commit by adding changes to it.
git commit --fixup <commit>: Create a fixup commit that will be squashed into another commit during interactive rebase.



concepts tobe cleared ?

git tag
git stach
git sub module

 
