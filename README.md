# Tutorial on git by SuperSimpleDev on YouTube
## Going through the process of building a git repository
### Using command prompt and visual studio code

// git commands
git init - git starts tracking changes in folder
git status - shows all changes between previous commit
git log - commit history
git checkout <commit_hash> - view previous commit
git add <file/folder> - changes that will be accepted for next commit
    git add file - pick individual file to add
    git add folder - all files in folder
    git add . - all files
git commit -m "message"- creates commit with message for updated files
    git commit -m "message" --amend - update previous commit instead of creating a new version
git branch -
git log -all --graph -shows the branching that is happening between earlier versions
git checkout master - switches to the latest commit in any given branch

If we go back to previous branches we can branch off the original main line.

git config --global alias.(shortcut) "" - allows you to make shortcuts for commands

Create file called .gitignore to create a directory that git will ignore.
write names of files named in .gitignore file

rm -rf .git - removes git from project

github is specifically designed for git repositories

bitbucket and gitlab are other options

local refers to files on the computer
remote refers to files online

git remote add origin + URL
git remote lists remote repositories linked
git remote -v  verbose gives more details

git push - upload to github
pull- downloading