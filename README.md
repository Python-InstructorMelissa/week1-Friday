# week1-Friday

# Git
to add new link to local folder to be added to git
git remote add origin <add git link here>

to updated repo link
git remote set-url origin <add git link here>


# Git flow
1. Create repo on git
2. Clone repo to device
3. Once ready git add * (this will add all files changed)
4. git commit -m "enter relevant message here"
5. git push


git status will show red for modified or changes files and green for files ready added but not committed

git blame <file name> = shows who edited the file and when
git rm <file name> = will remove any deleted files that didn't get auto removed via the git add
git rmdir -r <folder name> = will remove a whole folder including contents

To add token into git repo link so no login is required:
https://<token>@github.com/<username (or organization name)>/<repo name>.git

git checkout <branchName> = changes to another existing branch
git checkout -b <branchName> = creates a new branch and changes to it (the code will be imported from the branch you changed from)

git pull = brings any changes on github that are not local down to the device
git merge origin <branchName> = allows you to merge a different branches code into your current branch
    Every once in a while the branch will have the added words of MERGING added on meaning there is a merge conflict
