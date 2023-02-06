`Commit 0 (Main branch)` 

git init <br>
git add . <br>
git commit -m 'Commit 0' <br>

`Commit 1 (Main branch)`

git add . <br>
git commit -m 'Commit 1'<br>

`Commit 2 (Main branch)`

git add . <br>
git commit -m 'Commit 2'<br>

`Commit 3 (Checkout new branch 'bug-fix' from 'Commit 0' in 'main' branch)`

git log<br>
git checkout 'commit id'<br>
git checkout -b bug-fix<br>
git add . <br>
git commit -m 'Commit 3'<br>

`Commit 4 (bug-fix branch)`

git add . <br>
git commit -m 'Commit 4' <br>

`Commit 5 (bug-fix branch and resolve merge conflict)`

git merge main <br>
git add . <br>
git commit -m 'Commit 5' <br>

`Commit 6 (bug-fix branch)`

git add . <br>
git commit -m 'Commit 6' <br>

`Commit 7 (Checkout new branch 'bug-fix-experimental' from 'Commit 4' in 'bug-fix' branch)`

git log <br>
git checkout 'commit id'<br>
git checkout -b bug-fix-experimental<br>
git add .<br>
git commit -m 'Commit 7'<br>

`Commit 8 (bug-fix-experimental branch)`

git add . <br>
git commit -m 'Commit 8' <br>

`Commit 9 (bug-fix-experimental branch)`

git add . <br>
git commit -m 'Commit 9' <br>

`Commit 10 (Main Branch)`

git checkout main<br>
git add .<br>
git commit -m 'Commit 10'<br>

`Commit 11 (Merge 'bug-fix-experimental' branch with 'bug-fix' and resolve merge conflict)`

git merge bug-fix-experimental <br>
git add . <br>
git commit -m 'Commit 11' <br>

`Commit 12 (bug-fix branch)`

git add . <br>
git commit -m 'Commit 12' <br>

`Commit 13 (Merge 'bug-fix' branch with 'main' and resolve merge conflict)`

git merge bug-fix <br>
git add . <br>
git commit -m 'Commit 13' <br>