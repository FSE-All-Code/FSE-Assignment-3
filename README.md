`Commit 0 (Main Branch)` 

git init <br>
git add . <br>
git commit -m 'Commit 0' <br>

`Commit 1 (Main Branch)`

git add . <br>
git commit -m 'Commit 1'<br>

`Commit 2 (Main Branch)`

git add . <br>
git commit -m 'Commit 2'<br>

`Commit 3 (Checkout new branch 'bug-fix' from 'Commit 0' in 'main' branch)`

git log<br>
git checkout 'commit id'<br>
git checkout -b bug-fix<br>
git add . <br>
git commit -m 'Commit 3'<br>

`Commit 4 (bug-fix Branch)`

git add . <br>
git commit -m 'Commit 4' <br>

`Commit 5 (bug-fix Branch and resolve merge conflict)`

git merge main <br>
git add . <br>
git commit -m 'Commit 5' <br>