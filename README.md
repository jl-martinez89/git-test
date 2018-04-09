# Install and config of git
which git
git --version
git config --global user.name "Jose Martinez"
git config --global user.email jmartinezg.ca@gmail.com
git config --list

# Initialize a git repository
git init
git status

# Add files to the staging repository area
git add .
git add <file name>

# Committing files to the repository
git commit -m "First commit"

# Brief log of commits
git log --oneline

# Go back to a previous commit
git checkout <code> <file name>
git reset HEAD <file name>
git checkout -- <file name>

# Using an online repository
git remote add origin https://github.com/jl-martinez89/git-test.git
git push -u origin master
