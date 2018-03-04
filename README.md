# O Shop

This project demonstrates a simple e-commerce application for an imaginary organic shop. It is built with Angular, Firebase and Bootstrap 4 as the final project in my complete Angular course: 


## Running the Application

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. 

## Initializing this app module in local machine 

1: Clone repo

git clone https://github.com/nuelbruno/angularWeb.git

2: Install packages


npm install

3: Start server (includes auto refreshing) and gulp watcher


npm start


---------------------------------------------------------------------------------------------------
go to project folder

## initalize Git

get init

ls -la  // list all files

git add index.html // add to staging env

git status // to get status of staging

git add . // add all file to staging

git commit -m(msg) "init commmit // move all file from staging area to commit area


git log  // author and date and commit message

## Tracking file change

-change a file & ~git status => output status of file like committed or not

-git checkout index.html // will revert back the changes made to previoius staus for the file

-moveing file out of staging 
git reset HEAD index.html

## Delete a file

-when delete ~git status  => list the deleted files

-git checkout about.html // undo the delete

-git rm about.html // remove the files and commit

-git add --all // push all to staging

## Moving staging to commit and reverse

-git checkout hashnumber(bb70ele)

## Branch
-git branch  // * indicate current branch

-git checkout master // move to master branch or git branch branchname

-git branch newbranchname  bc2789(pc name)

-now git branch will list 2 branches

## Branch second part

-git branch // list all branch

-git branch app01 // creates new branch

-git checkout appo1 // moved to appo1 branch

-commit or changes made in child branch is not availbel to master branch. to merge child branch to master branch, see below

-git merge app01 // merge appo1 to master

-git branch -m app01 app1 // rename branch name

-git branch -D branchname // delete branch

### Download / Clone existing project from Github

-.gitignore // contains file need to be igonored in github

-Example
 --// builds/development/images/** // all files
-- node_modules

- package.json // will recreate all gitignired files

-git clone http://github_url  // download the code

- control + z to stop cmd execution

## Clone / Download and how to see branches

-gulp // automatically runs the code

-git branch -a // get all info about branch

-get checkout -b localbranchname origin/branchname

-mkdir dirname , mvdir

- git clone --mirror copy the clone url from github .git  // clone entire git project with all branches which is ivisible

-- type ls to view

- move to the proj folder
-git config --bool core.bare false
-git reset --hard // create all branches

now git branch will list all branches

## specific branch clone

git clone -b branchname https://githu_url


## To remove from git repositry

rm -dfr .git // move to project folder and enter the commet will remove the git setup

- after that start a new git like this
git init
git add .
git commit -m "init commint"












