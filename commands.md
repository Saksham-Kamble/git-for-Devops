Git Commands
1. Initialization
Commands for initializing a new repository.

git init
Initializes a new Git repository in the current directory.
2. Status & Information
Commands for checking the status of your working directory and logs.

git status
Displays the state of the working directory and the staging area. It shows which changes have been staged, which haven’t, and files that aren’t being tracked.

git log
Shows the commit history for the repository.

3. Configuration
Commands for setting up user information for commits.

git config --global user.name "Saksham-kamble"
Sets the global Git username for commits.

git config --global user.email "sakshamskm.kamble@gamil.com"
Sets the global Git email for commits.

4. File Operations
Commands for adding, removing, or restoring files in the Git repository.

git add <file>
Adds the specified file to the staging area. In the history:

git add nibi.txt
git add niba.txt
git add nibu.txt
git rm --cached <file>
Removes the specified file from the staging area without deleting the file from the working directory.
Example: git rm --cached niba.txt

git restore <file>
Restores the specified file from the staging area or last commit.
Example:

git restore nib.txt
git restore nibi.txt
5. Committing Changes
Commands for committing changes to the repository.

git commit -m "<message>"
Commits the staged changes with a commit message.
Examples:
git commit -m "adding niba.txt niba.txt"
git commit -m "add nibu.txt"
6. Branching
Commands for working with branches in Git.

git checkout -b <branch_name>
Creates a new branch and switches to it.
Example: git checkout -b dev

git checkout <branch_name>
Switches to the specified branch.
Example: git checkout dev

7. File Management (Outside Git)
Commands for file creation and removal in the system (non-Git).

touch <file>
Creates an empty file.
Examples:

touch niba.txt
touch nibi.txt
touch nibu.txt
rm <file>
Deletes a file from the system.
Example: rm nibi.txt

8. Miscellaneous
clear
Clears the terminal screen.

ls
Lists the files in the current directory.

history
Shows the command history.
