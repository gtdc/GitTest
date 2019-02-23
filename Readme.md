
### Creating a repo online for the <b>1st time</b>


```sh
$ echo "# GitTest" >> README.md
$ touch readme.md
$ git init
$ git add README.md
$ git commit -m "first commit"
$ git remote add origin https://github.com/gtdc/GitTest.git
$ git push -u origin master
$ username + password
```
### Adding changes and files to repo

```sh
$ git add . 				// . = add all changes
$ git add -u 				// To remove file from repo, that you removed locally
$ git commit -m "comment"
$ git push					// already connected staging to remote no need for -u origin master
$ username + password
```

### Remember username + password for every push

```sh
$ git remote set-url origin git@github.com:gtdc/GitTest.git
```

### Working together
```sh
$ begin by forking repo online
$ git clone REPO-LINK
```

### want to remove a file from online github repo but keep it locally
```sh
$ git rm --cached localFileName
# add localFilename to .gitignore file and then commit these changes
```
