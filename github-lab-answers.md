Commit 1

git init
git add
git push 

Commit 2

git pull
git reset 
git revert
The -- allow for different options when deviding what state you want the reverted file in.  --continue, --quit, --abort, --edit, are some options. 
If there are changes that you have commited that you want to rollback and take out, git reset would allow you to do that.

Commit 3

git branch (name of branch here)
git checkout (name of branch here
The default master should be the working code that is ready for actual use.  Using another branch allows you to make changes to the same code, without affecting the master code that everyone relies on.  

Commit 4

git merge would be used when you have multiple branches that contain files that you want to merged into a single branch.  It would be better to submit a pull request when working with a team of people.  Pulling provides an opportunity to review code submitted before moving onto the next step aka testing and production. 
git push origin master 

