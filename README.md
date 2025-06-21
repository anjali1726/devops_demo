# devops_demo
 this repo is created for demonistartion of devops demo activities
#### 1.download and install git and visual studio code
#### 2. open the work space directory in vscode
#### 3. modify the file content in workspace
#### 4. go to gitbash and check the status
     $ git status
     $ git add filename
     $git commit -m ""
#### 5. generate token key from github 
#### 6. How to resolve conflicts
     # pull the code from repo
     $git mergetool (open the file in vimdiff)
     # edit the conflict file (4th editor) and save it
     #then commit and push the file 
     # devops_demo

#### Directory Structure:

##### - Creating a Branch  
*Example:*  
- Master → Dev  
- Dev → Feature
- Formula:
src -> dest
    $git checkout src
    $git branch dest
##### - Committing to Branch  
*Example:*  
- Commit to Dev
- Formula:
   - identify the branch to commit
    $ git checkout branch-name
    $ git commit

##### - Merging Branches  
*Example:*  
- Feature → Dev

*Post Release:*  
- Release → Master  
- Release → Dev
- Formula:
  - src-> Dest (Feature ->dev)
   $ git checkout Dest-branch
   $ git merge src branch

##### - Backup of    
 - Tsgging
 Ex: main has to take backup
  feature has to take backup
  -Formula:
  $git checkout branch-name
  $ git tag tag_name
  