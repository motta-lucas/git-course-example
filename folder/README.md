# Example Git Repository

We are learning how to make commits

1. Make some changes
2. git add -- "staged" the change that we want to persist to our git history
3. git commit -m "adding ..." -- creates a commit

We are about to make a new commit

hi

goodbye

docs

# created the repo remotely
git clone <URL>

# create a ranch locally
git checkout <branch>
git checkout -b <new branch>
git add ...; git commit -m "...." (several times)
git push --set-upstram origin <new branch>

# create a new branch remotely
using the GitHub UI to create <branch>
git fetch --all
git checkout <branch>