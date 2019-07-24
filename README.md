# git-commands
In my opinion, the following syntax commands are commonly used in most of GitHub projects

## List of commands ##
Command|Description|
-------|-----------|
$ git clone <git_repo_url><br />For example, git clone https://github.com/MTamPham/git-commands.git |Clone a project from GitHub repository|
$ git init|Create an empty Git repository or reinitialize an existing one|
$ git remote add origin <git_repo_url>|Add a new remote to a repository|
$ git add -A|Add all (new, modified, deleted) files to index|
$ git add .|Add only new and modified files to index|
$ git add * |Same as git add . except files from current directory whose name begin with dot (.)|
$ git add -u|Add only modified and deleted files to index|
$ git add <file_path>|Add a specific file to index|
$ git commit -m "Message"|Records changes to the repository with a message|
$ git push|Update changes from index to the current branch of remote|
$ git push <your_remote> <your_branch>|Update changes from index to a specific branch of remote|
$ git pull|Fetch changes of current branch of remote|
$ git pull <your_remote> <your_branch>|Fetch changes of a specific branch of remote|
$ git fetch<br/>$ git checkout -m <revision> <file_path>|Fetch changes of the current branch, then checkout only necessary file(s) in a branch name (revision)|
$ git fetch --all|Fetch changes of all remotes|
$ git branch|List all branches in the working tree, the current branch is marked with asterisk (*)|
$ git branch <branch_name>|Create a new branch|
$ git branch -d <branch_name>|Delete a branch in the working tree|
$ git branch -D <branch_name>|Delete a branch with force in the working tree|
$ git branch -d -r <branch_name>|Delete a branch in remote|
$ git reset --hard <your_remote>/<your_branch>|Ignore changes in working tree by reseting the local branch to whatever is on remote|
$ git merge <another_branch>|Merge another branch to the current branch|
$ git merge --abort|Abort the merge process and try to reconstruct the pre-merge state after the merge has resulted in conflicts|
$ git merge --continue|Continue the merge process after the merge has resulted in conflicts and then has been resolved|
  

You can find further details in [Wiki](https://github.com/MTamPham/git-commands/wiki)
