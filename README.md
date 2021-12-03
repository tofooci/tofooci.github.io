# tofooci.github.io

## VScode에서 git에 커밋하는 방법
1. Vscode에서 __git clone__ 검색하고 브라우저에 접속하여 권한 허용
2. VScode에서 터미널을 열어(Ctrl+`) repository 연결된 것을 확인
3. 터미널에서 다음 명령어 순차적으로 입력
    * git add . #모든 변경사항을 저장하겠다는 뜻
    * git commit -m "메시지 내용" #로컬저장소에 저장
    * git push origin #GitHub(클라우드)에 저장 // #git remote 명령어로 원격저장소명을 알 수 있다.