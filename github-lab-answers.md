git init
git add
git push 

git pull
git reset 
git revert
The -- allow for different options when deviding what state you want the reverted file in.  --continue, --quit, --abort, --edit, are some options. 
If there are changes that you have commited that you want to rollback and take out, git reset would allow you to do that.

git branch (name of branch here)
git checkout (name of branch here
The default master should be the working code that is ready for actual use.  Using another branch allows you to make changes to the same code, without affecting the master code that everyone relies on.  

