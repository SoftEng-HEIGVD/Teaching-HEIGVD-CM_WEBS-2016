# Git & GitHub Help

* [GitHub: generating an SSH key](https://help.github.com/articles/generating-an-ssh-key/)
* [GitHub: resolving a conflict](https://help.github.com/articles/resolving-a-merge-conflict-from-the-command-line/)



## Add, commit and push all changes on the master branch

```
cd /path/to/repo
git add --all
git commit -m "I changed this and that."
git push origin master
```



## Retrieve team work from GitHub

```
cd /path/to/repo

# check if you have uncommitted changes
git status

# if there are any, commit them
git add --all
git commit -m "I changed this and that."

# pull changes
git pull origin master

# resolve conflicts if any (see GitHub help link at the top)
```
