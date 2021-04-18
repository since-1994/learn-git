- ls -al

- git init
  현재 디렉토리를 git으로 관리한다는 것을 의미합니다.
- git status
  현재 git 상태를 보여줍니다.
- git add [파일]
  버전 관리할 파일을 추가합니다 (Staging Area로 추가)
- git commit -m "<메시지>"
  새로운 버전을 생성합니다.
  - git commit -am "<메시지>"
    tracking중인 파일들을 대해 add와 commit을 한번에 해주는 명령입니다.
- git diff
  현재 파일들의 변경 상태를 보여줍니다.
- git reset --hard
  현재 파일을 직전 버전으로 되돌립니다.
  - git reset --hard <commit id>
    commit id를 가진 버전으로 되돌립니다.(master)
- git checkout <commit id>
  현재 파일을 commitId 버전으로 되돌립니다. commit id는 git log를 통해 확인합니다.
  - git checkout master
    현재 파일을 가장 최신의 버전으로 되돌립니다.
