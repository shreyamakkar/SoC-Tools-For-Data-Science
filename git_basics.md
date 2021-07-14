# Basic Git Commands
### To clone a repo
```
git clone [url]
```
### To add files to staging area
``` 
git add .
git add *
git add [filename]
```
```git add .``` adds all the files to the staging area, whereas ```git add *``` adds only the files in the current directory
### To remove a file and stage the removal
```
git rm [filename]
```
### To commit the staged files
```
git commit -m "[ some commit message ]"
```
### To push the commit to main branch
```
git push origin master
```
### To pull the changes
```
git pull origin
```
### To show the files that have to be committed
```
git status
```
## Working with branches
### To check the current branch andlist all the branches
```
git branch
```
Note the default branch is called main (which is the master branch)
### To create a new branch 
```
git branch [brach_name]
```
### To change to a branches
```
git checkout [branch]
```
### To merge a branch with the current branch
```
git merge [branch_name]
```
### To push to a different branch
```
git push origin [branch_name]
```
