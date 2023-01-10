# Linux Utils
command and utils

# 실행 프로세스 확인
ps -ef | grep [파일이름]
  
# Process가 사용하고 있는 자원 확인
lsof -t [PID]

# node back에서 실행하기 및 세션연결 해제
nohup node /var/www/[노드경로]/bin/www & disown

# nohup.out log 확인
tail nohup.out
cat nohup.out

# 특정 확장자 압축파일 생성
find ./ -name "*.mp3" -o -name "*.mp3"
find ./ -name "*.mp3" -o -name "*.mp3" | tar -czf [압축파일이름.tar.gz] -T -

# 현재위치 사용현황
du -sh

# 파일 시스템 사용현황
df -h