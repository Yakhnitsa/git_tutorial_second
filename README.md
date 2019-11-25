# GIT tutorial materials.
# Basic git commands

git config --list - list of git properties

git config user.name - show user name

git config --global core.editor -> configuring text editor by default.

git clone [url] [dir]
(git clone git@github.com:Yakhnitsa/git_tutorial.git git_tutorial2 -> use folder, isnstead by default git_tutorial folder to clone to.)

git diff -> Show files and lines, that have been modified after add commant.
git diff --staged -> Shows changes in file, that will be commited.
git diff -stat -> shows summary of which files were changed & numbe3r of added/deleted lines
git diff HEAD - changes after last commit
git diff HEAD^ - changes after previous commit

git remote -v

git status

git commit -m "message"

