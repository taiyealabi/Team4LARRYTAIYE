- [x] Git Flow Work FLow
- [x] Repository
- [x] Clone
- [x] Fork
- [x] Branch
- [x] Commit
- [x] Merge
- [x] Checkout
- [x] Push
- [x] Pull
- [x] Remote
        Add
        Remove
        Show
- [x] Status
- [x] Master branch


### GitFlow workflow

It is a tree-like architecture or a file structure that Git uses, where there is a reporsitory and a working copy of that repository. In order to move files between the repository and a working copy
This is a stream of work flow that communicates Git commands in every progams; either as a new task or a modified version as it applies. It begins with creating a new repository and a template copy of that same repository. Some of the commands are Clone, push pull, revert, commit etc…


## Repository:
After Git has been installed and configured, next is to put Git in the appropriate condition to start its operation. That is asking Git to start tracking changes in a particular project. We need to however decide where to put the project for Git to start tracking. This location is called a Repository. The repository can be a new folder created in a Windows directory on a Desktop.

The folder can be accessed via the command line by changing in to the windows directory in which that folder was created. Once in the root of the folder via the command Line, entering - Git init will tell Git to get everything ready to start doing its tracking.

A repository can also be created in the User Interface from the home screen after signing into your account, and then selecting 'New' or the 'Plus' sign (+) on the top right corner of the home page. See file attachment called 'Create a new repository.

Repository is the git folder inside a project. This Repository must have a name and a description which tracks all changes made to the files in the project. I also realize that all these changes made within the project file builds a history ovwhich tracks all changes made to the files in the project. I also realize that all these changes made within the project file builds a history ovetime. Meaning, if you delete the .git/ folder, then you delete your project history
 
![Screenshot added on creating a new repository](https://raw.githubusercontent.com/pyruskimo/LarryTaiyeImages/master/TestImage1.PNG)
![Scrrenshot added for Repository workflow](https://github.com/taiyealabi/TaiyeNJIT/blob/master/Repository%20Screenshot.JPG)


## Clone
A clone is a copy or the act of making a copy of a repository, for example, a copy of the the master branch. When a clone is made, files can be edited and Git will track the different changes made. The repository that was cloned is still connected to the remote version such that that changes that were made locally can be pushed to the remote to keep them synced.
Cloning is a process of creating an identical copy of a Git Remote Repository for a Project.
When we clone a repository, all the files are downloaded to the local master but the remote git repository remains unchanged. Making changes and committing them on your local repository (cloned repository) will not affect the remote repository that you cloned in any way. These changes made on the local master can be synced with the remote repository anytime the user wants..
![Gitcloneurl](https://github.com/taiyealabi/Team4LARRYTAIYE/blob/master/Cloning%20a%20Git.JPG?raw=true)


## Fork
Forking provides a way for each contibutor or developer to have their own serve-side repositoyr. This means that each ontributor has not one but two Git repositories: A private local repositories and a servier-side one. It can also be considered as a standard Git clone operation.
Forking is a process of creating a copy of a complete repository to the user’s GitHub Account from another account. When a user forks a repository, all the files in the repository are automatically copied to the user’s account on GitHub and it feels like the user’s own the repository. This process is similar to copying a folder from one drive to another drive in a computer. The user is then free to use this repository either for their purpose or experiment with changes in the code. Through git forking, the users can develop their own modifications to the code that belongs to someone else.
 
Forking a repository on GitHub is done for two main purposes:

Improving someone’s project/software or code: Improving can be that I am adding a new feature to the existing software/repository. For example, I navigate to a repository and liked the concept of the software, but then I have something else in mind that could be useful for the same software. I can fork the repository, develop the feature on my machine and send the changes to the owner of the repository.

Reusing the code in a project: A user can also make use of git fork to fork the repository of another user to use in their own project. The popularity of Git is also because people add their code, project, module, software, etc on GitHub as a public repository. Now other people are allowed to use that open source code to their project, which helps them to save their efforts and time. 
Note: Forking is allowed for public repositories without permission. But if the repository is private, one can only be able to fork if he or she has permission from the owner of the repository. (Please see screenshot below)

Instead of using a single server-side repository to act as the “central” codebase, forking gives every developer a server-side repository. This means that each contributor has not one, but two Git repositories: a private local one and a public server-side one.
![Screenshot for Git Fork](https://github.com/taiyealabi/TaiyeNJIT/blob/master/Git%20Fork%20Screenshot.JPG)


## Branch:
A branch represents an independent line of development. It is thought of as a way to request a brand new working directory, staging area, and project history. New commits are recorded in the history for the current branch, which results in a fork in the history of the project.
Getting the most out of Git will mean using branches often and effectively. Branches are easy to create, work with, delete and allow testing of different ideas. Assuming working on a project, and suddenly an idea comes to mind. Though uncertain if the new idea will work or not, instead of making lots of commit to the master branche and undoing <del>or reverting</del> the changes, a new branch can be created and the new idea test there on. And if the ideas do not work, the branch can be deleted and the master branch would not have been affected by the chnages. However if the idea does workout, those changes can be brought back to the master branch through a process called merging.
A branch is a separate line of development that enables the creation of a new branch with the git branch command. When a programmer fixes a bug or adds a new feature, he or she creates a new branch to make the changes in a safe way, without threatening existing, working code. 
![Added screenshot for Branch](https://github.com/taiyealabi/TaiyeNJIT/blob/master/Git%20Branch%20Screenshot.JPG)


## Commit: 
Commit implies telling Git to track the individual change to a file (or set of files). When a commit is made to save a work, Git creates a unique ID called "hash" that allows the keeping of record of the specific changes commited along with who made them and when. Commits usually contain a commit message which is a brief description of what changes were made.
Commits is an important part of the Git version control system. One way to think about commits is that they are a snapshot of a project during a certain moment in the project’s history. The "commit" command is used to save your changes to the local repository. Note that you have to explicitly tell Git which changes you want to include in a commit before running the "git commit" command. This means that a file won't be automatically included in the next commit just because it was changed. Instead, you need to use the "git add" command to mark the desired changes for inclusion

![Git commit](https://github.com/pyruskimo/LarryTaiyeImages/blob/master/Git%20Commit1.PNG)
![What happens](https://github.com/pyruskimo/LarryTaiyeImages/blob/master/commit%202.PNG)

## Merge
The "Merge" command is used to integrate changes from another branch. The target of this integration (i.e. the branch that receives changes) is always the currently checked out Master or Repository branch. While Git can perform most integrations automatically, some changes will result in conflicts that have to be solved by the user before the merge can be completed. 
Merging is a way of combining the work from two different branches together where a branch was created to develop a new feature and then combined back in to the main branch or master branch. Git merge will combine multiple sequences of commits into one unified history. In the most frequent use cases, git merge is used to combine two branches.

![Merge1](https://github.com/pyruskimo/LarryTaiyeImages/blob/master/Merge1.PNG)
![Added sreenshot for Merge](https://github.com/taiyealabi/TaiyeNJIT/blob/master/Merge%20Commit%20screenshot.JPG)

## Checkout
The command git clone is used to fetch the desired repository from the remote git server to a local computer and this process is known as cloning.  When you clone a repository, you start on the local repository’s master branch by default. To avoid any confusion and proper documentation purposes, it is advisable to make a new branch and work in that temporary branch. To make a new branch git checkout command is used. The command git checkout is used to check out the desired status of your repository be it any branch or a particular file. It can also be used for switching between existing local branches.
In summary, checkout has 3 uses:
1.	To create a new branch from the current branch.
2.	To switch between existing local branches.
3.	To check out and go to a particular status of a particular file.


## Push
The git push command is used to upload local repository content to a remote repository. Pushing is how commits are transfered from a  local repository on to a remote repository.
- It uses the following command: git push <remote> <branch>
After a local repository has been modified a push is executed to share the modifications with remote team members.
In its simplest definition, the Git push command can be taken as uploading the content to the remote repository.
After adding a feature, making changes or other tasks in the local repository, we can use the push command for uploading these changes to the remote repository (e.g. Github) so other team members can see it and may update their project accordingly.

![Before and after Git push diagram](https://github.com/pyruskimo/LarryTaiyeImages/blob/master/Git%20Push.PNG?raw=true)

## Pull
Git pull is a magical way to perform a combined operation of git-fetch & git-merge with a single command. “Pull,” which is self-explanatory, depicts that the user is trying to fetch something from the repository. In a way, “fetch” is not the right word because we already discussed git fetch command. If you think that fetching is all that Git Pull does, then why aren’t we satisfied by Git Fetch?
Git Pull will perform Git Fetch without telling the user and merge those changes automatically without asking from the user. ## Pull 
The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content. The git pull command is actually a combination of two other commands, git fetch followed by git merge. In the first stage of operation git pull will execute a git fetch scoped to the local branch that HEAD is pointed at. Once the content is downloaded, git pull will enter a merge workflow. 
![Screenshot for Git pull](https://github.com/taiyealabi/TaiyeNJIT/blob/master/Git%20Pull%20screenshot.JPG)

## Remote
Remote allows us to collaborate with others. It is responsible for syncing changes. It also records changes made through the git remote command and are used in conjunction with the git fetch, git push, and git pull commands. 

## Status
Git status command is used in Git to know the status of the working tree. It shows the state of your working directory and helps you see all the files which are untracked by Git, staged or unstaged. In shorter terms, Git will show you any difference in the current document and the Master file. Along with this, Git status will also show you the changed or new file in the repository.
The git status command displays the state of the working directory and the staging area. It lets you see which changes have been staged, which haven’t, and which files aren’t being tracked by Git.

![Usage](https://github.com/pyruskimo/LarryTaiyeImages/blob/master/Status.PNG)


## Master Branch
A branch in Git is simply a lightweight movable pointer to one of these commits. The default branch name in Git is master . As we start making commits, you're given a master branch that points to the last commit you made. Every time you commit, the master branch pointer moves forward automatically.

*![References](https://www.atlassian.com/git/tutorials/using-branches/git-checkout)
*![References](https://www.atlassian.com/git/tutorials/saving-changes/git-commit)
*![Reference]](https://www.atlassian.com/git/tutorials)
