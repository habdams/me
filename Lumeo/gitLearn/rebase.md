#### How to `git rebase`
```
$ git checkout main
$ git pull
$ git checkout --my-feature-branch
$ git rebase main


```

#### How to `git cherry pick`

git checkout to branch where you want to pull in commits from
```
$ git checkout --old-branch
$ git log (get the commit id of preferred commit)
$ git checkout --new-branch
$ git cherry-pick [890980 - commit id without this brackets] 
$ git cherry-pick [890980] -n // do a cherry pick with no commit 
```
