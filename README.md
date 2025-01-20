# gitworkshop2025

NAME : Utsav Sapkota

what is git?
GIt is a version control system.(it is simply a software run in the computer for specific purpose.)
 version control system is a tool to track the changes in code.
 * It is popular among the developer all around the world.
 * It is free and open source .
 * It is fast and scalable.


## uses of git ;

1. To track history of code .
2. To colaborate.

## what is github?
ans: GitHub is a web-based platform built on top of Git. It provides hosting  for Git repositories along with additional features to facilitate collaboration, project management, and deployment.

///some keywords meaning:///

1. Readme file (i.e. In this file there is description,features and other details about project.)
2. Repository(i.e. folders)
3. Add(staged) (i.e. It means to make that new file track by git ,after make changes or modified in code)  
     //add is first step after make change .
4. Commit (i.e. It means to finialize the changes or modified after add.)  
    //commit is second step after change to finialize.
5. untracked file (i.e. IT means git doesnot track that new file yet. )
6. modified file (i.e. It means there are changes or some modification happens in tthat file program.)
7. staged (i.e. It means it is ready to be committed it also mean to add.)
8. unmodified (i.e. It simply means there is no change in that file.)

 


step 1: download git in Pc.
step 2;
       TO configure the Git in terminal.

       1. git config --global user.name"your name"
       2. git config --global user.email"example@email.com"
       3. git config --list /or/ git config --l


### BASIC COMMANDS AND ITS USES (step by step ):

1. clone and status:
   
   ## step1: clone(making duplicate): cloning a reprository in our local machine(i.e. our laptop and Pc )form remote repositoty.

      command:  git clone<-link of reprository.>

   ## status: it display the status of code.
          
      command:  git status

2. Add and Commit:

 ## step 2: Add(staged)--adds new file(untracked file by git) or changed file(modified file) from working area to  Git repository .

            command to add : git add .  /or/  git add <file name>

 ## step 3: commit----It is a record of change or any modification happens in that file.

           command to commit : git commit -m"meaningful title"

3. Push command ::: upload local repo( form laptop/pc) content to remote repo(copy of a project stored in a github).
          
          command to push : git push origin main
          


