# Adding Folder 

Adding folder directoly to github from the vscode

the commands that we used for that were

first we created folder locally on ou system and added a readme file in it
then we see our status by using git status
we then proceed to commit the changes by using git commit -m "our message"
after that we need to connect to remote repository for that
craete a empty repo with same name on github copy the ssh url
then use command
git remote add origin git@github.comURL
it will connect with the repo
then we will use
git remote -v to see where we have connection

to push we will use

git push origin master
