# 2020-06-16 Git

- `git init`: create a git respoitrory in the current directory
- `git status`: tells you what is going on
- `git add [file name]`: puts the files that you want to take a snapshot of into a staging area 
- `git commit`: makes the snapshot of what is in the staging area
- `git log`: shows a log of commits
	- `git log --oneline`: shows a shorter oneline version of git log
- `git diff`: shows the changes to a file from current state to last state
	-`git diff HEAD~# <FILENAME>`: compares the changes made in the file, # is the number of commit versions back you want to go back
	-`git diff --staged`: compares files in the staged area
	-`git diff <commit ID number>`: shows the changes from that commit to head, commit ID number can be found in the commit log
- `git commit -m "type 1 line of commit message here"`: commits without opening nano to write commit message
- `git checkout <hash> <file>: referts back to the file you are on
	-`git checkout master`: goes back to current state of work

## Remotes


- `git push <where> <what>`: pushed to master
- `git pull <where> <what>`: takes remote master branch and brings it to local master branch

## Conflicts
- chance at the same place or in differenc places
