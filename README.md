오픈 만화번역 SNS 루나캣의 레거시입니다.

node.js를 기반으로 제작되었습니다. 서버 환경은 다음과 같습니다.

ubuntu 18.04
node.js 12.14.1
mariaDB

aws ec2 + s3

git - ec2 webhook 사용중

현재 완료된 기능

- REST API 기반
  - 회원가입
  - 글쓰기 CRUD
  - 이미지 업로드

- 파일 기반 세션 로그인/로그아웃

-----

DB 적용

sqlDump.sql 을 참고하여 데이터베이스를 사용
