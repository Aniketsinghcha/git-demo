'git init'=> Powers your folder to managed by git,and initialises a new empty repositry
respositry ,it also creates a .git folder that has all the relevant logic to 
manage versions of your project.

'working area'=> there can be mumtiples files that are not currenlty handled
by git,it means the changes done or to be done is not managed by git yet,the untracked
filed that we get when we run the command,git status,are the files that 
are in woring stage

'staging  area'=> the files in staging area shows what files are going to be the part ofthenext versions
,the staging area is the place where git knows what  changes
have been donw from last version to current version

'Repositry Area'=> this area contains the details of all of the
previous registered version,the files in this area,git knows and manages them
and now thier version history 

'git add <file_Name>'->add files to staging area from working area to staging area

'git rm --cached <file_Name> -> moves files from  staginga area to working area

'commit'->> it is like a particular version of the project.
it captures a snapshots  of the project's staged changes and created a version of it.

'git commit'-> register staging changes to commit

'git log'-->> prints all of the commit of the repositry


'git restore'-->it removes all file changes  from the staging area to be commited.this can beusefult,as it will restore the the last commited version

'difference between git restore and git rm'-->
 git restore is used for playing between git working area and git 
 stagged area  while git rm moves enitre file to untracking to working area,while restore command
 only play wuth changes made .perioddddddtttt. 

 'git commit -m  'your mssage'-->if we want to avoid opening a text editor
   like vim/nano to add commit message we use following command

   'git remote add <name of remote> <repo url>' -->
   this command helps us to add a new link to the remote repo and give
   a name to it.

  'git remote rm<name of remote>' --> this command deleted the remote connection

  'git add <file1> <file2> <file3>'--> thuis command will add multiple file changes together
   in the staging area
<<<just for pull purpose i am making this commit>>>
   
'git pull <remote name> <branch name>'-->downloads latest changes
###  recommended practice to do
   -make change
   -git add <files>
   -git commit
   -git pull
   -git push
   