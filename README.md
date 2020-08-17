2020-08-17-git-jss VT SWC Git lesson

##LOCAL

- `git init`: create git repository in current folder
- `git config --global user.name ""`
- `git config -- global user.email ""`

- `git status`: displays the state of the working directory and staging area. Shows which changes have been staged...
- `git add`: allows you to add a change in the working directory to the staging area
- `git commit`: saves or snapshots changes you've made to the staging area in Git project history
- `git config --global core.editor "nano -w"`: if default text editor is unset or you wish to change it, allows you to set it to nano

- `git log`: shows you your history
	- `git log --oneline`: shows you your 1-line version of commit history
- `HEAD`: where you're looking at in history

- `git diff`: shows changes you've made to file not already added to staging are
	-`git diff --staged`: shows changes you've made to file in staging area
- `git commit -m "MESSAGE"`: allows you to directly add in a comment without opening the nano editor

##REMOTES

- `git remote add origin <URL>`: adds URL with the name origin
- `git push origin master`: pushes the master branch to...
- `git pull origin master`: pulls the master branch from origin to local computer
- `git clone <URL>`: pulls someone else's repository to local machine


You can make changes to different parts of a file and will automatically merge
In a merge conflict, look for the `>>>` `===` `<<<` and fix the lines that conflict


-Learned how to clone and collaborage
