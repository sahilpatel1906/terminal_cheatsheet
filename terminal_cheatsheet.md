# Terminal Cheatsheet
---
## Directory Related Commands
- pwd : prints working directory
- ls : list all files and folders in current directory. adding -a flag shows hidden files (.files). adding -l flag shows detailed information about files.
- cd : changes directory. followed by .. for moving out of directory or by folder name to move into directory
- mv <original_name> <path/new_name> : can be used to move file to different directory or rename the file name.
- mkdir <name>: create a folder.

## File Related Commands
 - cp <name> <destination>: copy file to destination directory
 - rm <name>: removes file. adding -r flag removes entire folder.
 - touch <name>: create files. make sure to add file extention, i.e file.txt

## Git Commands
- git init : initialise git repository in current directory
- git add . : used to stage all changes in current directory. adding --all flag instead of . to stages all changes in all directories.
- git commit -m <message> : commit the staged changes. make the message short and verbose.
- git push origin main: push changes to GitHub. origin refers to the repository the changes are being pushed to. main refers to the branch the changes are pushed to.
- git status: shows current status of repository. staged/unstaged changes or commits information. can be shortened to gst.
- git log: shows logs of all commits made to repository
