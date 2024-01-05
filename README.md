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
