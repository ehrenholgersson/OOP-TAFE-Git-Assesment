# Part 2: Questions 
### Question 1.

Git, CVS and Mercurial

### Question 2.

Git enables a group of developers to easily share their code by uploading to a central location (repository). Maintaining multiple branches allow developers to work on and test new or incomplete features without impacting the main build. Git also provides version control features allowing developers to roll back to previous commits in cases where this may be required (for example a failed build or feature that has not panned out as intended)  

### Question 3.

Git Terms

Branch - branch in git is a series of changes or commits. These commits are separate from other branches until/unless  they are merged 

Pull - Pull is to download content from a remote repository

Push - Push is to upload content to a remote repository

Repository - A repository is the location where git stores all of the changes made to the project.

working copy - this is a repository that also stores the complete versions of project files, so that files can actually be used and/or modified.

Merge - a Merge will apply all changes made to one branch to another branch. 

### Question 4.
Occupational Health and Safety, Data security policies, Backup policies may apply (assuming backup procedures are in place for remote git server)

### Question 5.
Meld - allows visual two and 3 way comparison of files and directories, has support for git as well as several other version control tools
DiffMerge - another too that visually shows differences between two files or directories
Perforce Helix - is a three-way merging and side-by-side file comparison tool.


### Question 6.
The Git output will return a message with description of the conflict.

### Question 7
The easiest way to resolve a merge conflict, if it is a line change conflict, is to open the file identified as having the conflict and look for the conflict marker ("<<<<<<<"). After this you will see the conflicting lines listed either side of a divider ("======="), followed by ">>>>>>>" and the branch name. 
Decide on the code that you want to keep, and replace everything from <<<<<<< to >>>>>>> with the desired code, then stage changes and commit, making sure to outline in comments the reason for the commit (resolve merge conflict).

For a file merge conflict, you decide if the file in question should be included in the destination branch, then use either git add "filename" or git rm "filename" to add or remove the file.

## Question 8
Git revert will create a new commit with all changes made since a specified commit reversed.

### Question 9
Git reset will move both the head and the branch reference to a specified commit, depending on type of reset this can result in the loss of data that has not yet been committed. It can also result in "orphaned" commits which may be deleted by Git's garbage collection.

### Question 11
False

### Question 12
True

### Question 13
DevOps is a software development methodology intended to unify processes and practices used in development of a project with those used in its deployment and support. DevOps is useful for game developers as it can streamline communications and team management on a project, and can greatly reduce the time to build and deploy a project.

## Question 14
Some DevOps tools:

* Puppet - Puppet is a tool for automating server configuration
* Kubernetes - Kubernetes automates deployment and management of application containers.
* Jenkins - Jenkins help to automate building testing and deployment of software projects
* Incredibuild - Incredibuld is grid computing software which can distribute software compilation or other intensive tasks across multiple systems on a network

## Question 15
CI/CD stands for continuous integration/continuous deployment (or sometimes delivery). It automates building testing and deployment of small incremental updates to a project, with the aim to provide faster release cycles. 

[Return to README](/README.md)




