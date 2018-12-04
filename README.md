# GIT CheatSheet

#### Git configuration
   + `git config --global user.name "Full Name"` //set name
   + `git config --global user.email "you@appscode.com"`    // set email
   + 'git config --list'    //view configuration 

#### Git initialization 
   + `cd /home/user/my_project`     //open existing directory
   + `mkdir name`             //create directory
   + `git init`               // initialize .git 
   + `git add <file_name>`      //add file or stage file
   + `git add .`        //add all files or stage all file
   + `git commit -m 'C1:master msg'`    //commit updates
   
   
 #### Cloning an Existing Repository
   + `git clone https://github.com/user/project_name`  // clone repository from github
   +  `git clone https://github.com/user/project_name  new_name`   // clone repo with new name
   
 #### Check Corrent Status
   + `git status`   // check current status or notice changes 
   + `git status -s` // short status
   
 #### Viewing Changes
   + `git diff`     // compare with last commit (not staged)
   + `git diff --staged`    // compare with last commit (staged)
   + `git diff  <commitHash1> <commitHash2>` //compare changes in two commits
   +  `git show <commitHash>`       // changes in a single commit 
   
 #### Create and Delete File
   + `git add fileName.type`        //add file to git
   + `git rm fileName.type`         //remove file from git
   