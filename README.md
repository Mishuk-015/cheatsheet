# cheatsheet
//cheat sheet for git commands

cd~-returns to current directory


git config(moode)-mode is mode of configuration

git config user.name "name"-sets username

git config user.email "email"-sets mail

git config color.ui "true/false"-sets difference in color in commands

git config --list-gives current configuration

git config configuration_name-gives status of configuration


git init-initializes empty repository in cd

git status-gives status of files in repository

git add .-adds all modified/new file to staging area

git add filename-adds certain file to staging area

git commit -m "message"-adds files to repository from staging area,-m is for message

git diff-differentiates all files in repository and working area

git rm file.txt-deletes file from working directory & staging area


git revert #hash:it's the  opposite of a commit and then commit it. Better than git reset because doesn't change history

git revert -m #hash:it's the opposite of a commit and then stage it - ready for commit

git clean -f -d:remove untracked files and folders

git clone address of repository:opens repository in working area

ls -la:shows files in cd

git log:shows commit history


