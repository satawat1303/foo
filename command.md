## Edit Error
* git fetch // check client with github
* git merge // clone file 
* git pull // pull = fetch + merge
___
## Discard
* git checkout -- filenname.txt // undo
* git reset HEAD .. // discard add
* git reset --soft "HEAD^" // discard commit
* git log --oneline // number commit
___
## Remove
* git rm test.txt // delete file after push
___
## Recovery
* git reset HEAD test.txt
* git checkout test.txt
___
## ...
* git add .
* git stash // hide your update
* git pull // clone file to com
* git stash pop // recovery file
* git add .
* git commit -m "..."
* git push
___
## branch
* git checkout -b branchname // create & switch branch
* git push --set-upstream origin mew // push frist orther branch
* git checkout branchname // switch branch
* git merge branchname or git merge --no-ff branchname // รวม branch จาก branchname ไป branch ปัจจุบัน
* git branch -d branchname // remove branch
* git push origin --delete branch // update delete branch
___
## tag
* git tag v.1.1.1 // use tag
* git push --tags // push tags
* git tag --delete v.1.11 // remove tag in client
* git push origin --delete v1.1.1 // remove tag in server
