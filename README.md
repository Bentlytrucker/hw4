git init 명령으로 Working Directory 설정한다
echo 'Hello Git Project' > README.md 명령으로 Working Directory에 README.md 파일을 생성한다
git add README.md 명령으로 파일을 Untracked에서 Staged 상태로 변경한다
git commit 명령으로 파일을 Staged 상태에서 Unmodified 상태로 변경 (커밋 메시지를작성한다)

git push -u origin main 명령을 통해  본인의 아이디와 깃허브에서 발급 받은 토큰을 입력하면  원격 저장소에 README.md 파일이  push된다.
