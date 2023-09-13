# Ctrl+Future Training: Git Fundamentals  

## Training to introduce the cohorts how to push from local environment to Github

## Comman Linux Commands

  - Create a directory: **mkdir** name_of_the_directory
  - Change directory: **cd** name_of_directory
  - Create a file: **touch** name_of_file
  - List the content of folder: **ls**
  - Remove the file: **rm** name_of_the_file  
  - Remove the empty directory: **rmdir** name_of_the_directory
  
## Configure GitBash

  - **git config --global user.name "Your name"**  
  - **git config --global user.email "Your e-mail"**  
 
## Prepare your working environment

  - **mkdir websiteProject**
  - **cd websiteProject**
  - **git init**
  - **touch index.html**
  - **vim index.html** (to add content to the html file)

## Clone your repository

  - **git remote add origin (url from the github repo you created)** -use https format
  
## Push from your local environment to Github

 - **git status** -This helps to check the files on the staging area.
 - **git add index.html** - This adds your files to the staging area.
 - **git commit -m "Your commit description"** - The snapshot your staged content.
 - **git push origin master** -This command pushes the changes to the repository.
## Check your commit history

 -** git log** -Helps you to see commit history

## Checking the changes on the Github

 - Visit your repo link on Github to check the changes you made

## Creating another branch and merging it with the Master branch
 
 - **git branch newBranch** - Add new branch called as newBranch
 - **git branch** - List the branches
 - **git checkout newBranch** - Changes current branch to newBranch

## Push the new branch to the repo
 
 -** git push origin newBranch** - Pushing new branch to the repo
