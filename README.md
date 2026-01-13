# demo-repository
this is a demo repo.
<br>
Author- Richa Sharma
now making chnges..from here..
<br>
Authorsname - suraj 
So the vs code will show file as yellow colors bcoz some chnges has been fone but not saved right now...and a symbol of M has been shown..means modified..
<br>
OR ...we can even create new file in git-demo folder i.e., index.html ....so this file will be shown as untracked file when we do *git status*
<br>
--SO there are four status : 
1.untracked(U)= new files that git doesnot yet track 
<br>
2.modified(M)=changed 
<br>
3.staged = file is ready to be committed
<br>
4.unmodified= unchanged
<br>

#whenever we do some change ,we need to add that change , after that file get staged (ready to be committed )
<br>

#So saving changes is a two way process-->first add then commit
<br>
#TWO MORE COMMANDS : ADD & COMMIT 
<br>
ADD=adds new or changed files in your working directory to the git staging area.
<br>
syntax:: git add <-file name->
<br>
COMMIT = It is the record of change
<br>
syntax:: git commit -m"some message"
<br>

eg = git add index.html -->now the file name index.html will turn grenn 
i.e., ready to commit now
<br>
Similarly :: git add README.md -->also added that is ready to commit ...again go check git status-->everything seems to be modified now..
<br>
OR simply use "git add. " to ad or save all changes
//////NOW COMMIT//////
eg:: git commit -m "some meaningfull msg"
./// now all thses changes are in local system that is our pc or laptop  ,,they r not saved or added in gitHub...
For that we use PUSH COMMAND =upload local repo content to remote repo
syntax:: git push origin main
after that we can see the chnges made in vs code in github as well
// to move out of a directory use "cd .. "
//NOW MORE DETAILS----
Init COMMAND = used to create a new git repo/folder
either make manually  or frist move out of current folder and then type " mkdir name of repo "in terminal means ===> make new directory
eg= mkdirnlocalRepo 
so a new folder by name localRepo is made..
now this repository is just on local system..this is not a git repository 
so make it a git repo...do "git inint" -->now this is git repo and now can makw chnges in it
..
so make file in it now  (for eg)
index1.html &
sttyle.css
///now these files willl apper as untracked(U) ... so add them first (using git .), then commit ,then push
//now these changes are in local system...to mak them on github..make a new repo on github first
#After that use a command  " git remote add origin <-link-> " matlab jo nayi repo hum add kr rhe hn ab use origin kahenge..
#Ab ky set hua h , check it with "git remote -v" and this shows the name of localRepo repository
 #Another COMMAND -- git branch (to check branch) branch is basically a copy of a project on which a team has to work... default branch is "master"...
 Now we will rename this master branch to main branch or make a new branch by name main (why? : bcoz hr jagah main use hua h ) syntax: "git branch -M main
 --NOW we can push -- push krne s vo github pr bhi chnges show kr dega 


 //noww
 lets see WORKFLOW--->github repo--> clone--->made changes-->add them-->commit them-->push them to github.

 //GIT BRANCHES
 different portion of project on which different teams are working

 BRANCH COMMANDS!!!
 1.git branch (to chcek the branch,on which we are)
2.git branch -M main (to rename the branch name) , here  main is the name of branch
3.git checkout -b <-new branch name-> (to create new branch)
4.git checkout <-branch name->  (to move from one branch to another )
5.git branch -d <-branch name-> (to delete the branch).