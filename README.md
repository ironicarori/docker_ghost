# AWS Lightsail 인스턴스에 ghost 설치
1. aws lightsail 인스턴스에 다운로드 https://github.com/ironicarori/docker_ghost.git
   - 스크립트 실행 완료 후 콘솔에 "Hello from Docker!" 메시지가 보이면 성공!
2. install-docker.sh 실행하여 docker 설치
3. .env 파일을 자신에게 맞게 수정
   - exmaple.com을 자신의 url로 수정
   - MYSQL_ROOT_PASSWORD, MYSQL_PASSWORD 설정

# To-Do
1. url 및 passwd를 스크립트를 이용해 모두 설정 후 install 하게 처리할 필요가 있을까?
