# Revision and cloud 

## Version Control 

**What** is version control 
it is a system used to store multiple versions of the file , and record changes, it will help the programmer to track modifications, revert files to previous version, and compare changes. there are different versions of control systems. 

* **local version control** : one database on the local hard disk.

* **Centralized version control** : single server to store file versions and can be accessed by multiple clients. 

* **Distributed version control** : backup of the multiple files to prevent loss of the files in the centralized version control.

## What is Git 
**Git** is a distributed version control system to save files as snapshots , each snapshot is a version of the file , that stored on a local disk 

**How to download Git**

* For Windows 
[Download Git](https://git-scm.com/download/win)

* For Mac Os 
[Download Git](https://git-scm.com/download/mac)

* For Linux 
[Download Git](https://git-scm.com/download/linux)


**Download GitHub**
[Windows](http://windows.github.com)
[Mac Os](http://mac.github.com)

## How to Deal with Git through terminal 

* **Cloning** 
To Download the file in GitHub to your local machine 
$ git clone https://github.com/test

* **Files Status** 
To check the state of your file 
$ git status

* **Track a new file** 
$ git add filename 

* **Commit a file** 
To commit the changes of one file 
$ git commit -m “made change x,y,z”
To commit all changes 
$ git commit -a

* **Pushing changes** 
$ git push origin master

* **Seeing your remote** 
To view the short names of all remotes 
$ cd example

$ git remote -v

* **Create a new remote**
git remote add shortname url

* **Fetching** 
To pul data you don`t have 
git fetch [remote-name]

* **Pushing** 
To push your files to GitHub, from local data to cloud
$ git push origin master

* **Renaming remotes** 
$ git remote rename js jane

$ git remote

origin

jane

* **Removing remotes**
$ git remote rm jane

$ git remote

origin