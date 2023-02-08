# docker
도커 설치 & 도커 허브 이미지 업로드 & 도커 컴포즈 설치 등의 전반

1. VMware Workstation 다운 후 Ubuntu 설치

2. Ubuntu에 Docker 설치
  - apt 패키지 업데이트
  - docker 설치를 위해 필요한 패키지 설치
  - docker GPG key 추가
  - 레파지토리 설정
  - 도커 최신 버전 설치
  - hello-world를 실행하여 docker 엔진 설치 정상 확인

3. Docker hub
  - 회원가입 후 저장소 생성 (Repositories 메뉴)

4. Docker file 생성
  - docker file을 담을 디렉토리 생성
  - docker file 생성 및 편집
  - docker 이미지 빌드 (docker file이 있는 디렉토리 안에서)

5. Docker 이미지 저장
  - ubuntu 20.04 이미지를 컨테이너로 실행
  - apt 패키지 업데이트
  - git install
  - git version 확인
  - git 설치 상태 확인 (컨테이너 시작&접속, git 설치 확인)

6. Docker hub 이미지 업로드
  - ubuntu에서 docker 로그인 (이때 비밀번호는 토큰 코드)
  - docker 이미지 생성 -> [Username]/[저장소 이름]:[태그]
  - docker hub에 push

7. Docker-compose 설치
  - curl 명령어를 통해 docker-compse 설치
  - 컴포즈 파일을 실행 가능하도록 다운로드한 경로에 권한 부여
  - 심볼릭 링크 설정으로 path 경로 설정
  - 정상 설치 확인
  
8. Ubuntu에 MySQL 설치
  - 우분투 서버 업데이트
  - mysql-server 설치
  - MySQL 기본 설정
