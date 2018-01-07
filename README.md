# ssml.01
간단한 생성모델챗봇 만들기 (윈도우버전)

1. git 설치
    http://git-scm.com/download/win 접속하면 자동으로 다운로드 진행
2. python3.x 설치
    구글검색 python download
3. pycharm 설치
    구글검색 pycharm downlaod
4. pycharm 오픈후 git에 접속 (그전에 github.com에 가입필수)


- pycharm의 하단의 왼쪽아이콘 클릭 후 Terminal 탭크릭
    python -m http.server --cgi 8080
    혹은 python3 -m http.server --cgi 8080

- 크롬브라우저 오픈
    http://localhost:8080/cgi-bin/chatbot.py 입력

- Terminal Console에서 Error발생

- pip 으로 파이썬 모듈설치 필요
    pycharm의 File>Settings>Project:ssml01 - Project Interpreter에서 설정(오른쪽 화면의 + 클릭하여 새창에서 xxx로 검색)

- 먼저  konlpy 설치
    konlpy설치 jpype에러시 Jpype1 
    --> 설치에러시 JDK문제임 http://www.oracle.com/technetwork/java/javase/downloads/jdk9-downloads-3848520.html 
    --> Microsoft Visual C++ 빌드툴 설치에러시 http://landinghub.visualstudio.com/visual-cpp-build-tools
- JAVA_HOME 설정 (참조: http://macchiato.tistory.com/9)

