# H21-TIO4120
Tasks for TIØ4120


# How to work on github

## Windows

Preferably install [Git Bash](https://github.com/git-for-windows/git/releases/latest).

### Using Git Bash

Move to the desired folder/directory on your computer. Use the commands `ls` to see which files lie under the current folder/directory. Thereafter use `cd path_to_folder` to move into the desired folder. `cd` is "change directory". Once here, use `git clone https://github.com/GunGro/H21-TIO4120.git` to clone the repository from github into the current folder. Thereafter `cd` into the repository.

## Git

The most often used commands are `git status`, to see which files are edited since the last commited change. 
1. `git status`

Once you are done with a file for the day, use `git status` to see which files are modified. Thereafter use `git add path_to_edited_file' to track the desired files. Use `git status` again to see what is tracked for the next commit.
2. `git add path_to_file`

Once you have tracked all the changes needed for the next commit, then you are ready to commit. Use `git commit -m "commit message"`. Please keep the commit messages short and descriptive of the work done since the last commit.

3. `git commit -m "commit message"`

Now you have commited, but the remote repository on github is still not changed. You also have to push your local changes to the remote repository. This can be done using the command `git push`. 
4. `git push`

It is always good to start the day with pulling from the remote repository(github). This can be done with the command `git pull`. Then you local repository and the remote on github will be syncronised.
5. `git pull`
