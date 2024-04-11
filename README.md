## VSCode_MySQLHeatWave 
How to connect MySQL HeatWave service via VS Code using MySQL Shell extention


VS Code 에서 MySQL Shell extention을 이용해 MySQL HeatWave 서비스에 접속 및 쿼리 실행는 방법 

### 1. MySQL Shell 확장을 VS Code 에 설치
- VS Code 앱에서 왼쪽의 Extentions 클릭 > MySQL Shell 로 검색 > MySQL Shell extention 설치
![vscodemysqlshell](image.png)

### 2. MySQL Shell에서 MySQL HeatWave Connection 설정
- VS Code 앱에서 왼쪽의 새로 만들어진 MySQL Shell 메뉴(돌고래모양) 클릭 > 화면의 New Connection 클릭
![newconnection](image-1.png)

- Database Connection Configuration 설정
Database type은 mysql로 설정 후 **Basic탭**에서 MySQL HeatWave 서비스 private IP와 관리자 ID 입력
![setconnectionconf](image-2.png)
