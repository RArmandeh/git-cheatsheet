# git-cheatsheet
[@dwsclass](https://github.com/dwsclass) dws-dev-005-git

## **This Repository is about git for devops class bloodrina**

**Define the author name and author email to be used for all commits by the current user.**

**git config --global user.name "yourname"**      
**git config --global user.email "youremail"**

 1. You can use version control tools like git to Step-by-step management of the source code application. Git is a repository for keep source code and versioning.
        
 2. Repository is a strategy for accessing data that includes a set of commits and branches, tags, files. A good repository includes the following files:      **README.md, LICENSE, .gitignore.**
        
 3. A good document consists of three sections
        
        a. What is that repository and what is it made for?

        b. How to use it and get started with it?

        c. What should someone do if they want to contribute code?(Optional)
        
4. When you want to get a sample of an existing git repository, we should use git clone command. **#git clone**
        
5. For update and sync the local repository with the remote repository use **#git pull** command.
        
6. Difference between **checkout, revert, reset**
        
**Checkout-** Change the position of the head. Make a new branch and move between them.
        
**#git checkout –b <new-branch-name>**        
**#git checkout <other-branch-name>**

**Revert-** Returns to one or more previous commits, lose changes and add new commits. **#git revert**
        
**Reset-** Returns to one or more previous commits, keep changes and just remove commit. **#git reset**
    
7. **Merge-** Join two or more development histories together(Integrate into another branch e.g. “Master”)**#git merge <branch-name1><branche-name2>**
        
**Rebase-** All changes are added one by one to where they should be in Master. The timeline does not crash.**#git rebase**
        
8. You can use the **#git log** command to see the history of commites.
        
9. You can use the **#git diff** command to see the changes to a file.
        
10. You can tag specific points in a repository’s history as being important with use **#git tag <number of version>** command.
        
11. First read README.md and License file, so clone a sample of project in local system and create local branch, add change and commit them, after that merge local branch to master branch, if you have conflict, you should pull from remote branch and fix conflicts, finally, push to remote branch.
        
12. Branches allow you to fix bugs, or safely implement new ideas in a portion of your repository.You can be integrated by using **#git merg** and **#git rebase** commands.
