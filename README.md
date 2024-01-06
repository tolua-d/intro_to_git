# working directory
- area where all files, directories and changes are living all the time
- git init is to activate git in the directory
- touch "file name" to create file.

# staging area
- files and directories that we implicitly add to the staging area
(like the croschecking area)
- git add (file) will get the file from the working directory to the 
staging area
- git status is used to know what's been tracked, added, untracked etc on git
- git log will show you the history of your snapshots

# git repository
- where all snapshots are stored.
- git commit -m "message" to move files from the staging area to the repository.

- note: always add file to staging area before committing it to the repo!!
- git add *.filetype adds all files with the extension to the staging area while calling on git commit would move all files in the staging area to the repo.
- git add -A adds all files in the working directory including the hidden files.
- git reset HEAD <file>... is used to unstage files and so is git restore --staged <file>...
- to ignore files in git, create a file using the touch command and name the file as .gitignore. save every file you want git to ignore in this.
- mv command is used to rename files in the terminal. mn current_filename new_filename
- git branch is used to list the branches in the repo.
- to create a new branch and switch into it, use git checkout -b <branch_name>. the checkout command switches to this new branch.
- git checkout <branch_name> switches to this branch. commits in each branch are different from one another. you won't see a commit in one branch in the other basically unless they are merged using the command git merge <branch_name>
it's advised not to but if you want to delete a branch, using the command git branch -d <branch_name> does the trick.

git remote add origin url to link github to your workspace terminal
git remote -v to confirm it's been linked.
git push -u origin master to push your files straight to github for the first time.
git push origin master to continually push changes to github.