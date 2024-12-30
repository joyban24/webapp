# webapp
깃허브 사용법 연습용 저장소

test readme file


git init : 폴더 초기화, main branch 생성
git init 폴더명 : 새 디렉토리 만들고 저장소 초기화과정 한번에 할때
ls -la
git status
git add 파일명 : 스테이징
git commit -m "커밋 메세지" : 커밋
git commit -am "커밋 메세지 2번째부터" : 스테이징 & 커밋
git log : 저장된 버전 확인
git log --stat : 커밋관련 파일 내역 보기
git log --oneline : 한줄에 한커밋 보기
git log --oneline --branches --graph : 브랜치, 커밋, 그래프 한꺼번에 보기
git log main..apple : main branch에는 없고 apple branch에만 있는 커밋 보기
git remote add origin : 깃허브 포지트리 주소 HTTP
git remote -v : 확인
git push -u origin main : 깃허브 포지트리에 첫 푸시
git push : 두번째 푸시부터
