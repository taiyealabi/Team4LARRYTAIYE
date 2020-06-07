- [x] Git Flow Work FLow
- [x] Repository
- [ ] Clone
- [ ] Fork
- [x] Branch
- [x] Commit
- [ ] Merge
- [ ] Checkout
- [x] Push
- [ ] Pull
- [ ] Remote
        Add
        Remove
        Show
- [ ] Status
- [ ] Master branch


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
When we clone a repository, all the files are downloaded to the local master but the remote git repository remains unchanged. Making changes and committing them on your local repository (cloned repository) will not affect the remote repository that you cloned in any way. These changes made on the local master can be synced with the remote repository anytime the user wants.



