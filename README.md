

```sh
$ git flow init
$ git flow feature start a-new-feature
$ git add .
$ git commit -m "changes"
$ git push --set-upstream origin feature/a-new-feature
$ git flow feature finish a-new-feature
```

```sh
$ git flow bugfix start TCE-100
$ git add .
$ git commit -m "changes"
$ git push --set-upstream origin bugfix/TCE-110
```