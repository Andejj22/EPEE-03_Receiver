# EPEE-03_Receiver
Repo for project work KiCad files

## How to start working on this repo
First make sure you have git installed on your computer. For Windows OS it's probably easies to download "Git for Windows" and configure it according to the instructions. Linux shouls have git preinstalled and ready to work. After you have git ready and working, go to the directory you want to have your copy of the project in, and type
```
git clone https://github.com/Andejj22/EPEE-03_Receiver.git
```
When actually typing these leave out the brackets. Now you should have a local copy of this project. To start working, create a new branch and switch to it with
```
git checkout -b [your_new_branch_name]
```
And you're ready to work! It's good practice to name the branch after the feature you're working on. After you've done your work, it's time to commit and push the changes. Start by typing
```
git add .
```
This adds all the modifications to the list of things to commit. Then, you can commit the changes to the local branch by typing
```
git commit -m "your_commit_message"
```
Again, it's good practice to name what you've done within this commit. After committing, you can push the changes to the remote repository by
```
git push origin [your_branch_name]
```
This will create a new branch for this remote repository. After reviewing the changes, a pull request can be made to merge the changes to the master branch. 

Remember that this whole thing needs to be done for the first time only. After that, simply pulling the changes from the remote repository is enough when starting the work. This ensures that there will be no mis-match when merging the changes to the master branch. This can be done with 
```
git pull origin [branch_name]
```
