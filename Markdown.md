Git Commands 
1.Git clone : used to download an existing repository from GitHUb to your local machine
Syntax:  git clone TrainingNotes01
(or)
git clone https://github.com/sudhi02-code/TrainingNotes01.git

2. git status:
Shows the current state of your local working directory -including staged,unstaged and untracked files
Syntax:
git status

3. Creating and switching Branches:
3.1 git branch:
   used to create a new branch
   syntax:
   git branch <branch_name>
   example:
   git branch mainbranch
   
 3.2  switch to branch:
   used to switch from one branch to another branch
   syntax:
   git checkout <branch_name>
   example:
   git checkout main
   
3.3  create and switch together: this created a new branch and switches to it 
Syntax:
git checkout -b <branch_name>
example:
git checkout -b secondbranch

4. pulling the latest code:
 git pull : fetches and merges the latest changes from the remote repository to your current loacl branch
Syntax:
git pull origin <branch_name>
example:
git pull origin main

5. Committing and pushing changes:
5.1 git add: the git add command is used to add changes (New,modified or deleted files) from your working directory to the staging area
   Syntax : git add<file-name>
   example: git add index.html
   Note: git add does not save your changes permanently ie it just prepares them to actually save them  you need to run it
 Staging area: The staging area is a space between your working directory and your repository .It's where Git prepares your changes before commiting them it's likea "preview area"  where you decide what exactly will go into your next commit

5.2 git commit :  Command is used to save the changes you have staged into the local repository
   Syntax : git commit -m "message"
   example : git commit -m " added new html file"
   
5.3 git push : git push is used to send your local commits to a remote repository 
Syntax: git push origin <branch-name>
example: git push origin main
   
