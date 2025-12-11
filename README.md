# btcfutures-signal-system
# (1) git 초기화 (로컬에서 새로 시작할 때만)
git init

# (2) 원격 추가 (이미 clone 했다면 이 단계 생략)
git remote add origin https://github.com/YourUser/btcfutures-signal-system.git

# (3) 파일 스테이지
git add .

# (4) 커밋
git commit -m "Initial commit: add index.html"

# (5) 기본 브랜치 이름을 main으로 바꾸기 (필요시)
git branch -M main

# (6) 최초 푸시 (인증창이 뜨면 GitHub 아이디/토큰 입력)
git push -u origin main
