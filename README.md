# githubtest
test github code repo
command:
git clone https://github.com/rkandekar/githubtest.git #copy code from github to local
git status # check if local code has any changes with github
#now update the code locally
git status # after code update locally it will say to sync
git add firstGit.py # it will add firstGit.py file to staging area.Later staging area will be used to commit files when you run git commit
git status # now the firstGit.py will show as green. means firstGit.py is in staging area and ready to commit
git commit -m # will take all green marked file firstGit.py commit locally
git config --global user.email "rkandekar@gmail.com" # it might also ask for login with github user first time
git log # gives all history logs
clear # command to clear the console
git status # double to check if anything to commite
git push # push the code to github... push commited changes to remote server (github in this case)
