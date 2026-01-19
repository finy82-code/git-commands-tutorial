# Key Git Commands

## Configuring GIT

git config --global user.name "Finy Mathew"
git config --global user.email "finy82@gmail.com"

## Intializing a Repository

git init

## Cloning a Repository

git clone https://github.com/finy82-code/repository.git

## Staging and Committing changes

git add filename
git commit -m "Commit message"

## Viewing History

git log

## Branching

git branch new-branch
git checkout new-branch

## Merging

git merge branch-name

## Deleting Branches

git branch -d branch-name

## Handling Merge Conflicts

# Edit conflicted files

git add resolved-file
git commit

## Rebashing

git rebase branch-name

## Cherry-Picking
git cherry-pick commit-hash