Add email and username

git config --global user.email "<email>"
git config --global user.name  "<username>"

Initializing 

git init

Checking the status. Checking whether files are modified , newly added etc.

git status

To add a file in the staging

git add <filename>

To add all files in the staging

git  add *.* 
git add .

After creating a new repository in GitHub or any other service

git  remote add origin <location of the remote repo>

Committing the changes

git  commit -m <message>

Pushing the changes

git  push -u origin <branch name>

Get logs

git  log 

Get full commands

git  --help
![image](https://user-images.githubusercontent.com/30609998/184868299-4bc8d2a1-f015-4aa0-a007-254ba8cf6c42.png)
