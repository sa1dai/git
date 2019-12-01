git branch

git branch --list

git log --graph --oneline --all

git branch --no-merge

git branch --merge

git branch issue_54

git checkout issue_54

git checkout -b issue_55

git reset --hard acadbc7

What is a branch? It's just a label for the commit.

git tag v1.0

HEAD is a label for the current commit.

cat HEAD (file in the .git folder)

cat master (file in the .git/refs/heads folder)

cp master master_2

git checkout 850c658

'detached HEAD' state

git branch -D issue_54 (delete branch)

Rename branch:
1. git checkout issue_55 
2. git branch -m "issue_65"

git remote -v

git branch -u origin/develop

git branch --unset-upstream

git branch --contains 850c658