first of all i create a folder and add some files

after that i run the command in **GIT BASH** which is **git init**

after that i add all the files in the git which i used **git add .**

after that i check the status of files using **git status**



then i do some changes in file and check it



and if i uncertainly add some txt in file and off the laptop now i want to show the previous one code

so i use **git restore file name**



we can also backup the delete file using **git restore filename** 



and all the changes permanent save using **git commit -m "ui complete"**


**git log** it tell us how many snapshots(time commit/history) are there in our project


**git log** it show all the commits 

**git commit --amend -m "Removedd nice because boss says"** And in this command we can add the commits in previous ones commit.


-> Now We create a branch it means like **(Zip file)** of original one 

**git switch -c feature-revolution**
using this command we can create and open a new branch (it means when i do changes in this branch never do changes in original one)

if we want to merge the original branch(master) and the secondary branch we use this 
**git merge second_branch-name**

**git switch branch-name** using this we can switch the branch.

**git branch -d branch_name** we can delete the branch at any time.
