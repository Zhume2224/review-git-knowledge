
this is to brushup git knowledge - linkdin learning 
a

-Git add + file name / git add . (add all to the staging area)
Staging means : telling git that I want to save this file in my next commit

-Git status: to check if there are files in the stating area to need to be commited;

-Git commit -m "message or notes you want": locally a snipshoot has been created of this file.

//------------
Working on a file remotely:
Scenario:
You have a remote repo in github already, but you only have a file locally.
Steps to set a local repo: 
    1. Git init: make an empty repo locally.
    2. Git add . : add everything in the file to staging area
    3. Git commit -m " initial commit"
Connect local repo and remote repo:
    1. Git remote add origin " url copied from the remote empty repo in github"

//--------------
to clone a remote repo to local machine:
terminal:

git clone "url"
cd filename
code . : to open in vscode
work on files
git add.
git commit -m "initial coomit"
git push


Git diff: shows you what has been added to the file.
You can check it before staging.

If you wants to see the changed after stating;
Git add .
Git diff --cached

