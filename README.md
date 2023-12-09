# Project_KillingTime

GUIDE

필요한 프로그램
-Unity Editor_v.2022.3.4f1
-MariaDB
-IntelliJ (v.2023.2.3)
-Apache

개인 작업환경에 맞춰 수정하는 방법
1. 백엔드코드의 application.yml 파일의 데이터베이스 경로 수정(본인 환경에 맞게)

2. Apache 서버의 내부폴더에 Boarddoc_rank.html및 부수파일(css,image) 넣기

3. 백엔드 코드, Apache 서버 포트포워딩하기

4. 유니티내에서 통신주소 백엔드코드주소와 통일, 랭크 주소 Apache 서버 내 주소와 통일
(랭크주소 : RankWeb, 서버 주소 : GameStartSystem, LoginSystem, SignSystemCheck, SignSystemOK, SignSystem, StopButton)

5. intelliJ에서 killingtime/src/main/java 의 경로내에서 아무파일 실행(Run)

6. Apache 서버 실행

7. 유니티 first_scene부터 실행

유니티 협업툴
Plastic SCM, Unity devops
