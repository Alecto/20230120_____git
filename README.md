git config

git init

git status

git add .
git add filename

git commit -m "message"
git commit -a -m "message" <!-- git add + git commit -->
git commit --amend -m "message"

git log
git log --pretty=format:"%h - %an, %ar - %s"
git log -p -2

git rm --cached filename

git reset --hard HEAD^
git reset --hard HEAD~1

git stash

git branch
git branch -v
git branch new-branch-name

git checkout hash
git checkout branch-name
git checkout -b new-branch-name

git merge

git remote
git push
git clone

git pull <!-- git fetch + git merge -->
