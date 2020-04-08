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

## branch

### branch란 무엇인가?

- 마치 두개의 프로젝트 폴더를 따로따로 가지고 각각의 폴더에 작업을 하는것과 같은 효과를 내면서
- 동시에, 실험적인 작업이 끝났을때 그 소스를 원본 프로젝트로 매우 간편하게 자동화해서 병합해주는 기능

## merge

- 두개의 branch를 병합해서 하나의 버전으로 커밋

## merge conflict

- 병합 과정에서 충돌이 발생
- 사용자가 직접 수정하도록 Git이 자동으로 위임
- resolve conflicts : mark resolved : 충돌을 해결했다고 Git한테 알리는 작업

## clone

- 원격 저장소에 있는 파일들을 로컬 저장소로 복제

## push

- 로컬 저장소에 있는 새로운 버전들을 원격 저장소로 보냄

## pull

- 원격 저장소에 있는 새로운 버전들을 원격 저장소로 보냄

## 협업

- pull -> work -> commit -> pull -> push
