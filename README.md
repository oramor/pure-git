# Creation locally
By default branch with name "master" will be created simultaneously with repo.
```
git init
git add*
git commit -m "message"
> If you wish to rename master branch:
git branch -M main
git remote add origin git@github.com:oramor/pure-git.git
git push -u origin master
```

# Branch publishing
```
git push -u origin <local branch name>
```