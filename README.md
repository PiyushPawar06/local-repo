# This is a local repo - feature1 branch

# Git Commands 
<br>
git status - view status
<br>
git add "file name" - to add the file
<br>
git commit -m "message" - to commit the modified files with a message related to changes
<br>
git push origin main - to push the code from local repo(laptop) to remote repo(github)
<br>
git init - to make a new repo
<br>
git remote add origin "link of the new repo you created on github"
<br>
git remote -v (to verify the remote repo)
<br>
git branch - to check which branch we are on
<br>
git branch -m {new filename} - to rename the branch (here the branch name is changed to main from the pervious branch name)
<br>
git checkout - to navigate to a different branch
<br>
git checkout -b {filename} - to make a new branch
<br>
git branch -d {filename} - to delete the branch. note- you can't delete the same branch you're on.first change the branch and then delete the desired branch
<br>
git push -u origin main - to let git know all the push and updates are to be done on the main branch (-u is used for it so that next  time when you push something to remote repo you directly write git push instead of git push origin main) 