# Git Chapter 9 Notes

## Basic Git Command Pattern

git SUBCOMMAND [OPTIONS] [ARGUMENTS]

## Repository Inspection

git status
git branch --show-current
git rev-parse --show-toplevel
git rev-parse HEAD
git log --oneline --graph --all

## Staging and Committing

git add FILE
git diff
git diff --staged
git commit -m "Message"

Working directory → Staging → Commit

git add → git commit

## Branches

git branch
git switch NAME
git switch -c NAME
git branch -d NAME

## Merging

git merge BRANCH
git merge --no-ff BRANCH
git merge --abort

## Rebasing

git switch feature
git rebase main
git rebase --continue
git rebase --abort

## Cherry-Picking

git cherry-pick COMMIT
git cherry-pick -x COMMIT
git cherry-pick --continue
git cherry-pick --abort

## Stashing

git stash push -m "WIP"
git stash list
git stash apply
git stash pop

## Undoing Changes

git restore FILE
git restore --staged FILE
git reset --soft COMMIT
git reset --mixed COMMIT
git reset --hard COMMIT
git revert COMMIT

## GitHub

git remote -v
git push -u origin main
git push

## Chapter 9 Practice

I created a Git repository, created a commit, connected my local repository to GitHub, and pushed my main branch.

My local main branch and GitHub origin/main are synchronized.