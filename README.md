# 📗📗📗 List Of Useful Git Commands 📗📗📗

Git is a version control system that helps programmers and developers manage and track changes to their code at any time. It allows multiple people to work on a project simultaneously and also keeps track of who made what changes and when. Git stores these changes in a repository.

## 💎💎💎 Connect Github and Git Use SSH Connection 💎💎💎
### 1. In Github
Profile → Settings → SSH and GPG Key → SSH Keys → New SSH Key → Title →
### 2. VS Code Command In Terminal:
<pre>ssh-keygen -t ed25519 -C "yourmail@gmail.com"</pre>
Press Enter 3 times(If y/n then type y then enter)
<pre>cat ~/.ssh/id_ed25519.pub | clip</pre>
Here Copy a Key past any text document for checking perpose. If key is create then...
### 3. In Github
Past Public Key → ADD SSH KEY → Done...

## Push Project From Visual Studio Code To GitHub New Repository
<pre>
echo "# your_repository_name" >> README.md
git init
git add -A
git commit -m "first commit"
git branch -M main
git remote add origin repository_SSH_Location
git push -u origin main
</pre>

## Push An Existing Repository From The Command Line
Clone Your Github Project First.
### Git CLone Command
<pre>git clone repository_link
cd repository_floder_name</pre>

Now Add Your File This Folder

<pre>
git add -A
git commit -m "Your Comment"
git branch -M main
git remote add origin repository_SSH_Location
git push -u origin main
</pre>

### Fetch Down Any Changes From Global Repository To Current Repository
<pre>git fetch
git pull</pre>

## 💎💎💎 error: remote origin already exists 💎💎💎
### Check fach and pull location
<pre>git remote --verbose</pre>
If your fetch and pull location is right then you can push your file

## 💎💎💎 VS Code Command For Git 💎💎💎
### 1. To Open OR Close Explorer "VS Keyboard Shortcuts"
<pre>Ctrl + b</pre>
## 2. To Open A New Terminal "VS Keyboard Shortcuts" 
<pre>Ctrl + Shift + `</pre>

## 💎💎💎 Set Git UserName and Email On The Command Line 💎💎💎
<pre>
git config --global user.email abc@gmail.com
git config --global user.name abc
</pre>
#### Check Git UserName and Email On The Command Line
<pre>
git config --global user.email
git config --global user.name
</pre>

## 💎💎💎 Pull Project From GitHub To Visual Studio Code 💎💎💎
Open VS Code > Install An Extension > GitHub Pull Requests (GitHub) > settings > Command Palette > git clone >  clone from github > give link of your repo > select repository location > create folder > select > File > Open Folder > Select Your Folder > 
Done

## List of Top Useful Git Commands
Git commands are crucial for efficient collaboration and project management. In this article, we’ll explore a list of important Git commands like git commands to push, git commit command, git pull command, and git push command, etc that will help to improve workflow and optimize productivity. These are a Git Commands list that can be used frequently on Git.

### 1. git --version
used to show the current version of Git
<pre>
git --version
git -v
</pre>

### 2. git help
Take help from the Git help section for different commands and other errors
<pre>
git help
git -h
git --help
</pre>

### 3. git config --global user.name " "
Sets configuration values for your user name on git
<pre>
git config --global user.name "abc"
git config --global user.name def
</pre>
### 4. git config --global user.name
Check Git User Name
<pre>
git config --global user.name
</pre>

### 5. git config --global user.email " "
Sets configuration values for your user email on git
<pre>
git config --global user.email "abc@gmail.com"
git config --global user.email def@gmail.com
</pre>

### 6. git config --global user.email
Check Git Email
<pre>
git config --global user.email
</pre>

### 7. git init
To create a local git repository for us in our store folder. This will help to manage the git commands for that particular repository.
<pre>git init</pre>

### 8. ls
To see directories and files in the current directory.
<pre>ls</pre>

### 9. ls -la
To see hidden directories and files within the current directory.
<pre>ls -la
ls -lart</pre>

### 10. git status
To see what’s changed since the last commit. It shows all the files that have been added and modified and are ready to be committed and files that are untracked.
<pre>git status</pre>

### 11. git add index.html
To add a file index.html to the staging area to track its changes.
<pre>git add index.html</pre>

### 12. git reset
To revert from Tracking staged area to Untracked area
<pre>git reset</pre>

### 13. git add fileName
To add a specific list of files to the staging area.
<pre>git add index.html</pre>

### 14. git add –all
To add all files of the current directory to the staging area.
<pre>git add --all
git add -A</pre>

### 15. git commit -m ""
To commit our changes(to save our changes) and provide a message to remember for future reference.
<pre>git commit -m "Created a Readme.txt"</pre>

### 16. git add *.txt
To add all text files of the current directory to the staging area.
<pre>git add *.txt</pre>

### 17. git add docs/*.txt
To add all text files of a particular directory(docs) to the staging area.
<pre>git add docs/*.txt</pre>

### 18. git add docs/
To add all files in a particular directory(docs) to the staging area.
<pre>git add docs/</pre>

### 19. git add "*.txt"
To add text files of the entire project to the staging area.
<pre>git add "*.txt"</pre>

### 20. git log
To check the history of commits for our reference.
<pre>git log</pre>

### 21. git diff
To figure out what changes you made since the last commit.
<pre>git diff</pre>

### 22. git reset head license
To undo the staging of the file that was added in the staging area.
<pre>git reset head license</pre>

### 23. git checkout –license
To Blow away all changes since the last commit of the file.
<pre>git checkout –license</pre>

### 24. git commit -a -m “ ”
To add any of our tracked files to the staging area and commit them by providing a message to remember.
<pre>git commit -a -m “Readme.md”</pre>

### 25. git reset –soft HEAD^
To undo the last commit and bring the file to the staging area.
<pre>git reset –soft HEAD^</pre>

### 26. git reset –hard HEAD^
To undo the last commit and remove the file from the staging area as well(In case we went horribly wrong).
<pre>git reset –hard HEAD^</pre>

### 27. git reset –hard HEAD^^
To undo the last 2 commits and all changes.
<pre>git reset –hard HEAD^^</pre>

### 28. git remote add origin
These commands make a bookmark which signifies that this particular remote refers to this URL. This remote will be used to pull any content from the directory and push our local content to the global server.
<pre>git remote add origin https://github.com/madaan123/MyAlgorithms.git</pre>

### 29. git remote add <address>  
To add new remotes to our local repository for a particular git address.
<pre>git remote add <address></pre> 

### 30. git remove rm
To remove a remote from our local repository.
<pre>git remove rm</pre>

### 31. git push -u origin master
To push all the contents of our local repository that belong to the master branch to the server(Global repository).
<pre>git push -u origin master</pre>

### 32. git clone https://github.com/madaan123/MyAlgorithms.git
To clone or make a local copy of the global repository in your system 
(git clone command downloads the repository and creates a remote named origin which can be checked by the command – git remote -v).
<pre>git clone https://github.com/madaan123/MyAlgorithms.git</pre>

### 33. git branch Testing
To create a new branch named Testing.
<pre>git branch Testing</pre>

### 34. git branch
To see all the branches present and current branches that we are working on.
<pre>git branch</pre>

### 35. git checkout Testing
To switch to branch Testing from the master branch.
<pre>git checkout Testing</pre>

### 36. git merge Testing
To merge the Testing branch with the master branch.
<pre>git merge Testing</pre>

### 37. git branch -d Testing
To delete the Testing branch.
<pre>git branch -d Testing</pre>

### 38. git checkout -b admin
To create a new branch admin and set it as the current branch.
<pre>git checkout -b admin</pre>

### 39. git branch -r
To look at all the remote branches.
<pre>git branch -r</pre>

### 40. git branch -D Testing 
To forcefully delete a branch without making commits.
<pre>git branch -D Testing</pre>

### 41. git tag
To see the list of available tags.
<pre>git tag</pre>

### 42. git checkout v0.0.1
To set the current tag to v0.0.1.
<pre>git checkout v0.0.1</pre>

### 43. git tag -a v0.0.3 -m “version 0.0.3”
To create a new tag.
<pre>git tag -a v0.0.3 -m “version 0.0.3”</pre>

### 44. git push –tags
To push the tags to the remote repository.
<pre>git push –tags</pre>

### 46. git stash
To move staged files to the stash area which is present in the staging area.
<pre>git stash</pre>

### 47. git stash pop
To get back the files that are present in the stash area.
<pre>git stash pop</pre>

### 48. git stash clear
To clear the stash folder.
<pre>git stash clear</pre>

### 49. git rebase
Three tasks are performed by git rebase
1.	Move all changes to master which are not in origin/master to a temporary area.
2.	Run all origin master commits.
3.	Run all commits in the temporary area on top of our master one at a time, so it avoids merge commits.
<pre>git rebase</pre>

### 50. git config --global color.ui
To see different colors on the command line for different outputs
<pre>git config --global color.ui true</pre>

### 51. mkdir
Create a directory if not created initially.
<pre>mkdir demo</pre>

### 52. cd
To go inside the directory and work on its contents.
<pre>cd demo</pre>

### 53. cd ..
To get out of current directory
<pre>cd ..</pre>

