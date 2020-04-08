# How to use Git

## commit

1. working copy - unstaged files
2. add - move a file to staged files
3. index, staging area - staged files
4. commit - create a new version with the files in the staging area

## discard

- unchange the file to the last commit

## reset

- reset current branch to a certain commit
- hard : discard all working copy changes
- mixed : keep working copy but reset index

## revert

- 버전을 유지한채로 되돌린 버전으로 commit을 생성
- 여러 단계 밑의 버전으로 되돌릴 경우 순차적으로 revert 해줘야 충돌이 안생김
