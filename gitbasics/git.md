##THIS IS HOW I CREATED MY OWN GIT REPOSITORY

- FIRST OF ALL CREATE A FOLDER ON YOUR LINUS HOME OR WORKING DRECTORY. 
- THEN DO THIS COMMAND git init, THIS WOULD INITIALIZE GIT ON THAT FOLDER AND CREATE A FOLDER CALLED .git, WHEN YOU DO THE COMMAND git  status.

- TO KNOW THE STATUS OF YOUR GIT = git status. i.e "DO THIS IN THE WORKING FOLDER OF YOUR GIT FILE DIRECTORY.
- YOU CAN CREATE A NEW FILE AND EDIT IT OR YOU CAN JUST DO =code . TO OPEN A VS CODE EDITOR INSTANCE.
- TO ADD A FILE TO THE STAGING AREA DO =git add filename
- TO RETURN A FILE BACK OR REMOVE FROM THE STAGING AREA DO= git rm --cached filename
- TO COMMIT A FILE IN THE STAGING AREA "GETTING IT READY" DO= git commit -m " then anything you want to write inside"
- TO RENAME YOUR MAIN BRANCH FROM DEFAULT"MASTER" TO MAIN OR ANOTHER NAME ```git branch -M branchname```
- THEN TO ADD A NEW BRANCH BRANCH TO THE GIT LINUX FILE= git branch filename
- TO SWITCH TO ANY BRANCH 
```bashls 
git branch branchname.
```

- TO SYNC YOUR GIT FOLDER ON YOUR LINUS OS AND THE REPO YOUR GIT SITE= git remote add origin [THEN THE URL OF THE REPO].
- TO UNSYNC BOTH DO = git remote remove origin
- TO CHECK THE DESTINATION THE FILE IS GOING ON BOTH THE LINUX MACHINE AND THE GITHUB SITE ```git remote -v```
- TO PUSH THE FILE IN YOUR GIT LINUX MACHINE TO THE REMOTE"GIT SITE" DO=git push -u origin main
To add an image to your Readme file on github/linux machine .... First create an images folder in your main folder and put a picture there, hen open the readme file you want to input the picture and do this syntax= ![the name you want to name the picture](the imaages folder/the name of the picture)