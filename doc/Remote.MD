#Github Remote Command

###Show all remote site
```sh
$ git remote -v
$ git-commands	https://github.com/skywalker-wu/git-commands.git (fetch)
$ git-commands	https://github.com/skywalker-wu/git-commands.git (push)

Result:
<site name> <Url>
```
###Add remote site
```sh
$ git remote add <site name> <Url>
$ git remote add git-commands https://github.com/skywalker-wu/git-commands.git
```
###Remove remote site
```sh
$ git remote rm origin
```

###Rename remote site
```sh
$ git remote rename <old> <new>
```

###Push to remote site
```
$ git push <site name> <local branch>:[remote branch = master]
$ git push git-commands master
```

###Get update from remote site
    git pull <site name> <local branch>

####Reference
[http://blog.csdn.net/pgmsoul/article/details/7883706](http://blog.csdn.net/pgmsoul/article/details/7883706)
