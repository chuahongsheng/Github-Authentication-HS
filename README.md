# Github-Authentication-HS
Git Hub Authentication 

To keep the account secure, we must authenticate before we can access certain resources on GitHub. When you authenticate to GitHub, you supply or confirm credentials that are unique to the user to prove that you are exactly who you declare to be.

Each way of accessing GitHub supports different modes of authentication.

•	Username and password with two-factor authentication

•	Personal access token

•	SSH key

# 
##  Git Hub Commands

### Setup
1. git config --global user.name “[firstname lastname]”     
set a name that is identifiable for credit when review version history

2.  git config --global user.email “[valid-email]”   
set an email address that will be associated with each history marker

3. git config --global color.ui auto    
set automatic command line coloring for Git for easy reviewing

### Setup & Init


4. git init     
initialize an existing directory as a Git repository

5. git clone [url]  
retrieve an entire repository from a hosted location via URL

### Stage & Snapshot

6. git status   
show modified files in working directory, staged for your next commit

7. git add [file]   
add a file as it looks now to your next commit (stage)

8. git reset [file]     
unstage a file while retaining the changes in working directory

9. git diff     
diff of what is changed but not staged

10. git diff --staged   
diff of what is staged but not yet commited

11. git commit -m “[descriptive message]”
commit your staged content as a new commit snapshot

### Branch & Merge

12. git branch  
list your branches. a * will appear next to the currently active branch

13. git branch [branch-name]    
create a new branch at the current commit

14. git checkout    
switch to another branch and check it out into your working directory

15. git merge [branch]  
merge the specified branch’s history into the current one

16. git log     
show all commits in the current branch’s history


 ## 4 GitHub commands that will be most likely used often in the real project as they are basic commands. They are used to commit new changes to the remote repository under new branches.


1. git checkout
2. git commit -m "message"
3. git push
4. git pull

