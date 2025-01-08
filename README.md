# List-of-Useful-Git-Commands

Git is a version control system that helps programmers and developers manage and track changes to their code at any time. It allows multiple people to work on a project simultaneously and also keeps track of who made what changes and when. Git stores these changes in a repository.

## Set Git UserName and Email
<pre>
git config --global user.email abc@gmail.com
git config --global user.name abc@gmail.com
</pre>

## Create a new repository on the command line
<pre>
echo "# List-of-Useful-Git-Commands" >> README.md</br>
git init</br>
git add -A</br>
git commit -m "first commit"</br>
git branch -M main</br>
git remote add origin https://github.com/prodipalways/</br>
git push -u origin main
</pre>

## Push an existing repository from the command line
<pre>
git remote add origin https://github.com/prodipalways/</br>
git branch -M main</br>
git push -u origin main
</pre>

## List of Top Useful Git Commands
Git commands are crucial for efficient collaboration and project management. In this article, we’ll explore a list of important Git commands like git commands to push, git commit command, git pull command, and git push command, etc that will help to improve workflow and optimize productivity. These are a Git Commands list that can be used frequently on Git.
### 1. git help</br>
Take help from the Git help section for different commands and other errors.</br>
<pre>git help</pre>

### 2. git config</br>
To set the basic configurations on Git like your name and email.</br>
<pre>git config</pre>

### 3. git config –-global user.name “ ”</br>
Sets configuration values for your user name on git.</br>
<pre>git config –-global user.name “Ashish Madaan”</pre>

### 4. git config –-global user.email ” “</br>
<p>Sets configuration values for your user email on git.</p> 
<pre>git config –-global user.email ashishmadaan6@gmail.com</pre>

### 5. git config –-global color.ui
To see different colors on the command line for different outputs.</br>
<pre>git config –-global color.ui true</pre>

### 6. mkdir
Create a directory if not created initially.</br>
<pre>mkdir store</pre>

### 7. cd
To go inside the directory and work on its contents.</br> 
<pre>cd store</pre>

### 8. git init
To create a local git repository for us in our store folder. This will help to manage the git commands for that particular repository.</br>
<pre>git init</pre>

### 9. git status
To see what’s changed since the last commit. It shows all the files that have been added and modified and are ready to be committed and files that are untracked.</br>
<pre>git status</pre>

### 10. git add Readme.txt
To add a file Readme.txt to the staging area to track its changes.</br>
<pre>git add Readme.txt</pre>

### 11. git commit -m “ ”
To commit our changes(taking a snapshot) and provide a message to remember for future reference.</br>
<pre>git commit -m “Created a Readme.txt”</pre>

### 12. git log
To check the history of commits for our reference.</br>
<pre>git log</pre>

### 13. git add
To add a specific list of files to the staging area.</br>
<pre>git add</pre>

### 14. git add –all
To add all files of the current directory to the staging area.</br>
<pre>git add --all</pre>

### 15. git add *.txt
To add all text files of the current directory to the staging area.</br>
<pre>git add *.txt</pre>

### 16. git add docs/*.txt
To add all text files of a particular directory(docs) to the staging area.</br>
<pre>git add docs/*.txt</pre>

### 17. git add docs/
To add all files in a particular directory(docs) to the staging area.</br>
<pre>git add docs/</pre>

### 18. git add “*.txt”
To add text files of the entire project to the staging area.</br>
<pre>git add “*.txt”</pre>

### 19. git diff
To figure out what changes you made since the last commit.</br>
<pre>git diff</pre>

### 20. git reset head license
To undo the staging of the file that was added in the staging area.</br>
<pre>git reset head license</pre>

### 21. git checkout –license
To Blow away all changes since the last commit of the file.</br>
<pre>git checkout –license</pre>

### 22. git commit -a -m “ ”
To add any of our tracked files to the staging area and commit them by providing a message to remember.</br>
<pre>git commit -a -m “Readme.md”</pre>

### 23. git reset –soft HEAD^
To undo the last commit and bring the file to the staging area.</br>
<pre>git reset –soft HEAD^</pre>

### 24. git reset –hard HEAD^
To undo the last commit and remove the file from the staging area as well(In case we went horribly wrong).</br>
<pre>git reset –hard HEAD^</pre>

### 25. git reset –hard HEAD^^
To undo the last 2 commits and all changes.</br>
<pre>git reset –hard HEAD^^</pre>

### 26. git remote add origin
These commands make a bookmark which signifies that this particular remote refers to this URL. This remote will be used to pull any content from the directory and push our local content to the global server.</br>
<pre>git remote add origin https://github.com/madaan123/MyAlgorithms.git</pre>

### 27. git remote add <address>  
To add new remotes to our local repository for a particular git address.</br>
<pre>git remote add <address></pre> 

### 28. git remove rm
To remove a remote from our local repository.</br>
<pre>git remove rm</pre>

### 29. git push -u origin master
To push all the contents of our local repository that belong to the master branch to the server(Global repository).</br>
<pre>git push -u origin master</pre>

### 30. git clone https://github.com/madaan123/MyAlgorithms.git
To clone or make a local copy of the global repository in your system 
(git clone command downloads the repository and creates a remote named origin which can be checked by the command – git remote -v).</br>
<pre>git clone https://github.com/madaan123/MyAlgorithms.git</pre>

### 31. git branch Testing
To create a new branch named Testing.</br>
<pre>git branch Testing</pre>

### 32. git branch
To see all the branches present and current branches that we are working on.</br>
<pre>git branch</pre>

### 33. git checkout Testing
To switch to branch Testing from the master branch.</br>
<pre>git checkout Testing</pre>

### 34. ls
To see directories and files in the current directory.</br>
<pre>ls</pre>

### 35. ls -la
To see hidden directories and files within the current directory.</br>
<pre>ls -la</pre>

### 36. git merge Testing
To merge the Testing branch with the master branch.</br>
<pre>git merge Testing</pre>

### 37. git branch -d Testing
To delete the Testing branch.</br>
<pre>git branch -d Testing</pre>

### 38. git checkout -b admin
To create a new branch admin and set it as the current branch.</br>
<pre>git checkout -b admin</pre>

### 39. git branch -r
To look at all the remote branches.</br>
<pre>git branch -r</pre>

### 40. git branch -D Testing 
To forcefully delete a branch without making commits.</br>
<pre>git branch -D Testing</pre>

### 41. git tag
To see the list of available tags.</br>
<pre>git tag</pre>

### 42. git checkout v0.0.1
To set the current tag to v0.0.1.</br>
<pre>git checkout v0.0.1</pre>

### 43. git tag -a v0.0.3 -m “version 0.0.3”
To create a new tag.</br>
<pre>git tag -a v0.0.3 -m “version 0.0.3”</pre>

### 44. git push –tags
To push the tags to the remote repository.</br>
<pre>git push –tags</pre>

### 45. git fetch
To fetch down any changes from the global repository to the current repository.</br>
<pre>git fetch</pre>

### 46. git stash
To move staged files to the stash area which is present in the staging area.</br>
<pre>git stash</pre>

### 47. git stash pop
To get back the files that are present in the stash area.</br>
<pre>git stash pop</pre>

### 48. git stash clear
To clear the stash folder.</br>
<pre>git stash clear</pre>

### 49. git rebase
Three tasks are performed by git rebase </br>
1.	Move all changes to master which are not in origin/master to a temporary area.
2.	Run all origin master commits.
3.	Run all commits in the temporary area on top of our master one at a time, so it avoids merge commits.</br>
<pre>git rebase</pre>

### 50. git –version
used to show the current version of Git</br>
<pre>git –version</pre>
