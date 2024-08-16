
## Reference commands

Creating the repo you have 2 options to add him to your machine

If you created a empty repo, you can clone him using

```shell
git clone git@github.com:username/git-commands.git
```

Or, if you started to code without a git repo, you can use this commands

```shell
git init

git remote add git@github.com:username/git-commands.git

git add /path/to/file

git commit -m "a message about your changes"

git push origin main
```

Above we have many commands, here I will explain then

clone -> you make a clone of remote repo on your pc, creating a local repo
init -> initialize the versioning at repo
remote add -> adding a remote origin to your local repo (you can use other host platform like, gitlab, bitbucket, etc)
add -> add your changes to send to your repo
commit -> add the changes to history of repo, with the identification of the commit we can, revert, compare, and refer the changes
push -> with push we send all changes(commit) to remote repo
