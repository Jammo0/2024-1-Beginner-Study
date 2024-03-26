1주차때 배운 내용
================
## 우리가 Git을 배워야 하는 이유.
1. 코드의 수정 관리 필요
2. 파일 관리 필요
3. 개발은 혼자 하는것이 아님
4. 버전 관리의 필요성
## Git으로 파일을 관리하는 법
1. 디렉토리에 git 저장소 만들기 > a. git init
2. git으로 관리를 그만 하고 싶다면? > rm -r .git
3. Git으로 관리할 대상 등록하기 > a. git add
4. 파일 수정 후 로컬 저장소로 옮기기 > a. git  commit
5. 모든 파일 한 번에 등록 > git add .
6. 하나씩 등록 > git add <파일명>
7. unstage로 되돌리기 > git rm --cached <file>
8. git에 커밋하기 > git commit -m "<commit message>"
## 협업을 하려면?
GitHub를 사용하세요
## Commit Message - type
feat : 새로운 기능을 추가 했을때
refactor : 기존 코드를 개선 했을때
fix : 버그를 수정 했을때
chore : 코드 이외의 설정을 바꿨을때
docs : 문서화
test : 테스트 코드
## GitHub에 올리기 앞서
git remote add origin <주소>
git branch -M main
git push -u origin main
## GitHub에 올리기
git add <파일명>
git commit -m “commit message”
git push origin main

<https://github.com/Jammo0/Jammo0.git>
