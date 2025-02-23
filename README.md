# Example git repository

we are learning how to make commits.
#  git add git_tutorial.py --> to stage the file after change has been made.
# git status --> to check which files are staged.
# git commit -m "some desc"
# git stash --> to temporary log changes
# git stash pop --> to put the above change back in the file.

# git checkout -b feature/docs  --> Switched to a new branch 'feature/docs'
# git branch feature/docs --> Creates a new branch but does NOT switch to it.
# git branch --> to look at the number of branches 

# git checkout master --> Switched to branch 'master'
# git merge fix/security --> merge branch with master branch
# git log --> to look at the log file
# git branch -d branch_name --> delete feature branch after merge


# https://git-school.github.io/visualizing-git/ --> Visualizing Git
# https://learngitbranching.js.org/ --> Check out this website for the GitGame

# create a new repository on the command line

# echo "# Git-basic-commands" >> README.md
# git init
# git add README.md
# git commit -m "first commit"
# git branch -M main
# git remote add origin https://github.com/PreeshuS/Git-basic-commands.git
# git push -u origin main

# …or push an existing repository from the command line

# git remote add origin https://github.com/PreeshuS/Git-basic-commands.git
# git branch -M main
# git push -u origin main


# When on a feature branch in VSCODE, and you want to merge remote change to 
# git fetch origin main --> fetch any change that we don't have on local machine
# git merge main --> this will merge all fetched changed to feature branch on local

# is same as

# git pull origin main --> 
