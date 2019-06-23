SET CONFIG VALUES

$ git config --global user.name ""
$ git config --global user.email ""
$ git config --list

#######################################
$ INITIALIZE A REPOSITORY
$ git init

#######################################
$ BEFORE FIRST COMMIT
$ git status

#######################################
$ ADD GITIGNORE FILE
$ vim .gitignore

#######################################
ADD FILES TO STAGING AREA
$ git add -A
$ git status

#######################################
REMOVE FILES FROM STAGING AREA 
$ git reset 
$ git status

#######################################
$ git add -A
$ git commit -m "initial commit"
$ git status 
$ git log

#######################################
CLONING A REMOTE REPO
$ git clone <url> <wherer to clone>
$ git clone ../remote_repo.git .
$ git clone <url> .

#######################################
VIEWING INFORMATION ABOUT THE REMOTE REPOSITORY
$ git remote -v 
$ git branch -a

#######################################
PUSHING CHANGES
$ git pull origin master // check if any other changes happened during this time
$ git push origin master

#######################################
CREATE A BRANCH FOR DESIRED FEATURE
$ gitbranch calc-divide
$ git checkout calc-divide

#######################################
PUSH BRANCH TO REMOTE
$ gi push -u origin calc-divide
$ git branch -a 

#######################################
MERGE A BRANCH
$ git checkout master 
$ git pull origin master
$ git branch --merged 
$ git merge calc-divide
$ git push origin master

#######################################
DELETING A BRANCH 
$ git branch --merged 
$ git branch -d calc-divide
$ git branch -a 
$ git push origin --delete calc-divide
