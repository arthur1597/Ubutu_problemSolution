# Ubutu_problemSolution
우분투 클립보드 공유와 공유폴더가 안될때 해결법

우선 터미널에 sudo apt update 먼저해보기 
이후 sudo apt upgrade도 해보고 안될시 해결법


1.가상디스크 삽입 클릭 후 왼쪽 디스크 클릭
2. 열린 파일 빈곳에 우클릭후 터미널 열기
3.ls 입력 이후 sudo ./VBoxLinuxAdditions.run 입력

그리고 폴더 접근 권한 없을시는 sudo adduser (사용자명) vboxsf입

그래도 클립보드가 안될시 sudo -s 혹은 su-를 입력 후
apt-get install build-essential linux-headers-generic 입력하면 됨
