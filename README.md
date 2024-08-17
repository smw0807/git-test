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

```
git switch main
git push backup --all
```

main 브랜치의 커밋들을 backup 저장소에 업로드한다.

echo "some" > some.txt
mkdir somedir
echo "some2" > somedir/some2.txt
✘ songmin-u@M1Max  ~/Desktop/git/git-test   main  git status
현재 브랜치 main
브랜치가 'origin/main'에 맞게 업데이트된 상태입니다.

추적하지 않는 파일:
(커밋할 사항에 포함하려면 "git add <파일>..."을 사용하십시오)
some.txt
somedir/

커밋할 사항을 추가하지 않았지만 추적하지 않는 파일이 있습니다 (추적하려면 "git
add"를 사용하십시오)
git clean -f -d
some.txt 제거
somedir/ 제거

git status
현재 브랜치 main
브랜치가 'origin/main'에 맞게 업데이트된 상태입니다.

커밋할 사항 없음, 작업 폴더 깨끗함
