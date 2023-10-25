## Git

- 협업을 할 때 Git 사용법

1. 브랜치에서 작업하는 동안 master에 변화가 X
    1. A 브랜치를 만들고, 커밋을 만든 이후 master로 돌아와서 merge
2. 브랜치에서 작업하는 동안 master 변화 O
    1. master에 commit을 만들어두고 merge
3. 브랜치에서 작업하는 동안 master 변화 O + 같은 파일도 수정되어 있을 때
    1. B 브렌치를 만들고, (같은 파일 수정) commitd을 만든 이후 master에 (같은 팡리 수정) commit을 만들어두고 merge

- Git branch 생성
```git branch '생성할 branch 이름'```

- 내가 찾고 싶은 brach로 이동하는 방법
```git checkout  'branch 이름' ```

- master에 branch에 있는 파일들을 merge 할 때
```git merge 'brach이름'```

- branch를 삭제하고 싶을 때
```git branch -d 'branch이름'```