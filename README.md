```
git branch --unset-upstream
```

```
git remote add upstream https://github.com/smw0807/git-test
git remote -v
touch README.md
git add .
git commit -m "readme"
git push
```

```
git fetch upstream main
```

```
echo "main3" > main3.txt
git add .
git commit -m "commit
dquote> test1
dquote> test2"
git push
git log --oneline --all -n2
git push upstream main
```
