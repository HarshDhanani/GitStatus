# GitStatus
IMP GIT COMMANDS


-----------------------FIRST ROUND----------------------
Commands: 
{FIRST TIME ONLY}

git init --> for create an empty git repo(local)

git remote add origin "REMOTE URL" 

git status

git add -A       

--> this command will send all the files to the staging area (check with 'git status' command that everyhting is in green or not)

{Before doing commit first time we need to execure this 2 commands}

git config --global user.name "YOUR NAME"
git config --gloabal user.email "YOUR EMAIL" 


git commit -m "YOUR COMMIT MESSAGE/COMMENT"
git push -u origin master --> this will send all the files from git(local) to github(remote)

-->then it will ask you the remote user and password


-->after editing some code on remote url you have sync with the local repo as well for that the command is 

git pull origin master


------------------SECOND ROUND-------------------
status
add
commit
