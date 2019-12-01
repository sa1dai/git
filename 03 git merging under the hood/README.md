fast-forward merge:
1. git checkout -b "iss53"
2. git commit -m "test" --allow-empty
3. git checkout master
4. git merge iss53 (fast forward merge)

3-way merge:
1. git commit -m "test" --allow-empty
2. git commit -m "test" --allow-empty
3. git commit -m "test" --allow-empty
4. git checkout master
5. git commit -m "test on master" --allow-empty
6. git merge iss53

merge 'recursive' strategy

merge strategies (https://git-scm.com/docs/merge-strategies)

patience strategy

ignore-all-space

git merge --abort

git merge -s recursive -X ignore-all-space other_branch

:wq

gpg

gpg --list-keys

gpg --list-secret-keys --keyid-format LONG

git config --global user.signkey your_key

git commit -S -m "signed commit"

git log -n1 --show-signature

git merge -S other_branch