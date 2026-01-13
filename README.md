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
