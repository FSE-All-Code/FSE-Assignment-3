`Commit 0 (Main Branch)` 

git init <br>
git add . <br>
git commit -m 'Commit 0' <br>

`Commit 3 (Checkout new branch 'bug-fix' from 'Commit 0' in 'main' branch)`

git log<br>
git checkout 'commit id'<br>
git checkout -b bug-fix<br>
git add . <br>
git commit -m 'Commit 3'<br>

`Commit 4 (bug-fix Branch)`

git add . <br>
git commit -m 'Commit 4' <br>

`Commit 7 (Checkout new branch 'bug-fix-experimental' from 'Commit 4' in 'bug-fix' branch)`

git log <br>
git checkout 'commit id'<br>
git checkout -b bug-fix-experimental<br>
git add .<br>
git commit -m 'Commit 7'<br>

`Commit 8 (bug-fix-experimental Branch)`

git add . <br>
git commit -m 'Commit 8' <br>