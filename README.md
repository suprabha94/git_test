Course 1 exercise 
Basic GIT commands:
1. To initialize a folder as git repository on local system:
      git init
2. To check your Git repository's status:
      git status
3. To add files to the staging area of your Git repository:
      git add .
4. To commit the current staging area to your Git repository:
      git commit -m "message"
5. To check the log of the commits to your Git repository:
      git log --oneline
6. To check out a commit:
      git checkout <commit's number> filename
7. To discard the effect of the checkout operation and restore the state:
      git reset HEAD filename
      git checkout -- filename
8. To push the commits to the online repository:
      git push -u origin master
9. To clone an online repository to your computer:
      git clone <repository URL>
