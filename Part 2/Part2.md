# Part 2: Questions 
### Question 1.

Git, CVS and Mercurial

### Question 2.

Git enables a group of developers to easily share their code by uploading to a central location (repository). Maintaining multiple branches allow developers to work on and test new or incomplete features without impacting the main build. Git also provides version control features allowing developers to roll back to previous commits in cases where this may be required (for example a failed build or feature that has not panned out as intended)  

### Question 3.

Git Terms

Branch - branch in git is a series of changes or commits. These commits are seperate from other branches until/unlees they are merged 

Pull - Pull is to download content fro a remote repository

Push - Push is to upload content to a remote repository

Repository - A repository is the location where git stores all of the changes made to the project.

working copy - this is a repository that also stores the complete versions of project files, so that files can actually be used and/or modified.

Merge - a Merge will apply all changes made to one branch to another branch. 

### Question 4.
Occupational Health and Safety, Data security policies, Backup policies may apply (assuming backup procedures are in place for remote git server)

### Question 5.

### Question 6.
The Git output will return a message with description of the conflict.

### Question 7
The easiest way to resolve a merge conflict, if it is a line change conflict, is to open the file idetified as having the conflict and look for the conflict marker ("<<<<<<<"). After this you will see the conflicting lines listed either side of a divider ("=======")followed by ">>>>>>>" and the branch name. 
Decide on the code that you want to keep, and replace everything from <<<<<<< to >>>>>>> with the desired code, then stage changes and commit, making sure to outline in comments the reason for the commit (resolve merge conflict).

For a file merge conflict, you decide if the file in question should be included in the destination branch, then use either git add "filename" or git rm "filename" to add or remove the file.

## Question 8
Git revert will create a new commit with all changes since a specified point reversed.

### Question 9

### Question 11
False

### Question 12
True



