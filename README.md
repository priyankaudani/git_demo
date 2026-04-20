# git_demo
This is a description
<br>
Few GIT commands: 

git --version
<br>
git config --global user.name "My name"
<br>
git config --global user.email "Email"
<br>
git config --list
<br>
git clone "(link)"
<br>
pwd
<br>
ls
<br>
git cd
<br>
git status
<br>
git add *file name*
<br>
git add .
<br>
git commit -m "Message"
<br>
git push origin main
<br>
cd .. --------> Used to go back a folder
<br>
mkdir   -----------> To make new directory
<br>
git init    ------> To make it git repository
<br>
git remote add origin <link>
<br>
git remote -v    -----> To verify remote directory
<br>
git branch 
<br>
git branch


<br>
git push -u origin main  ----------> Can use git push next time directly.
<br>
git branch  -----> To check branch
<br>
git branch -M (new_name)  -----> To rename the branch
<br>
git checkout <-branch name -> -------> To navigate
<br>
git checkout -b <-new_branch_name->  ----> To create a new branch
<br>
git branch -d <-branch_name> -----> To delete branch

# Merge Code ( Two ways: Using Pull Request or use Terminal)

git diff <--branch name ->   -----------> To compare commits, branches, files & more
<br>
git merge <--branch name ->   -----------> To merge 2 branches
<br>
# PULL
git pull origin main
<br>
# UNDOING CHANGES
<p>
Case 1: Staged changes: (Only added)
<br>
git reset <-file name->
<br>
git reset -----------> All files reset at once
<br>
Case 2: Commited Changes: (For one commit)
<br>
git reset HEAD~1
<br>
Case 3: Commited Changes: (For many commits)
<br>
git log ------> Get the hash/code of the change we want to go back to and replace that with hash below
<br>
git reset <-commit hash->
<br>
git reset --hard <-commit hash->
</p>
