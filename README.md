this one is started locally   
this one is not a git repo yet

ls -a   there is not hidded .git file



# demo 2

git init
to turn this into a git repo
we get the master branch 


git status
git add .
git status
git commit -m "title" -m "description"

git push origin master
// push to origin in master branch  origin means to this directory

error...   we haven't cloned it from github
so it donesn't know where to push it...
first we need to make a connection...   because we didn't create it in github we create in local

1. create an empty repository ........  copy ssh
2. git remote add origin paste_copied_ssh_link
3. check for any remote repositories that we have connected to this repo 
   git remote -v
//  remote means somewhere else not in this computer
// used to add reference to remote repository on github 


4. git push origin master
origin is the location of our repository...  master is the branch which we want to push to

// i can say default push to here  ( upstream )
5. git push -u origin master
// in fture we can use git push







now check the work flow for both...  demo-repo  and demo-repo2

