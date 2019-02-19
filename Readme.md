
### Creating a repo online for the <b>1st time</b>\
echo "# GitTest" >> README.md\

``` sh
$ touch readme.md
$ git init
$ git add README.md
$ git commit -m "first commit"
$ git remote add origin https://github.com/gtdc/GitTest.git
$ git push -u origin master
$ username + password
```
### Adding changes and files to repo

``` sh
$ git add . 				// . = add all changes
$ git commit -m "comment"
$ git push					// already connected staging to remote no need for -u origin master
$ username + password
```