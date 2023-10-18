# Part 3

## 3.1 - how to install git for windows 

### Download Git

Download git [here](https://github.com/git-for-windows/git/releases/download/v2.42.0.windows.1/Git-2.42.0-64-bit.exe)

1. Double click on the downloaded installer.

2. Accept the user agreement and click install.

![EULA](/Part3/Images/EULA.png)

3. Wait for install to complete and select Finish

![Done](/Part3/Images/done.png)

4. Open either Windows command prompt or git bash and setup name and email with the following commands:

```
git config --global user.name "<Username>"
git config --global user.email "<emailaddress>"
```

## 3.2a - Git Best Practices for commits

* Keep Comments Clear and concise - It should be easy to understand quickly from reading the comment what has been changed in a commit
* Try to limit commits to one fix or change - this makes it easier to write clear comments and also to revert that change if necessary
* Use Branching when working on a new feature - This allows a feature to be worked upon without interfering with other work
* Commit working, tested code - Confirm code is behaving as expected before sharing it with others.

## 3.2b - Git Best Practices for repos
* Limit each repository to one project
* Include a README in each repository
* For collabarative work, prefer branching over forking
* Use Large File Storage
* Name the repository in a way that clearly identifies the project
 
## 3.3 - Git Workflow

1. Install Git if not already
2. If new project, create repository on Github
3. Clone repository  
4. Setup any required branches (If new project add staging and development branches, if working on new feature setup feature branch)
5. Ensure correct branch is checked out
6. Make changes/fixes to code
7. Test changes before commit
8. Add/Commit changes with clear comments
9. One team member responsible for merging updates to staging to check for merge conflicts and perform other testing before merging into main branch.

[Return to README](/README.md)