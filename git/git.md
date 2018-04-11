# Collaborating
4. git remote add upstream git@github.com:whatever/project.git
5. git fetch upstream
6. git merge upstream/master
6. git checkout -b branches/exercise1 origin/branches/exercise1


# Several useful commands
* roll back a file to specific commit
```git log readme.txt```
```
commit 513531b70676ce96c9254706a05af45fd264ad49
git checkout  513531b70676ce96c9254706a05af45fd264ad49 xx
```
* see all remotes
```git remove -v```

* clone in current directory
```git clone https://...xx.git .```

* clone specific branch
```git clone -b <branch> <remote_repo>```


# Excluding
Removing from local repository and not put it on gitignore\
E.g. when you have given example config files but customized accordingly but don't want to track the changes.\
Add a line like in ```.git/info/exclude``` as in `.gitignore`
