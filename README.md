# mysql

## 실행

C:\Bitnami\wampstack-7.3.13-0\mysql\bin 폴더로 이동.

    mysql -uroot -p

패스워드 입력

-uroot : user root 의 권한으로 접속.
-p : 비밀번호 물어봄.

## 명렁어

    CREATE DATABASE "name";

데이터 베이스 생성

    DROP DATABASE "name";

데이터 베이스 삭제

    SHOW DATABASES;

데이터 베이스 목록 보기

    USE "name";

이제부터 "name"에 대한 데이터베이스를 대상으로 명령을 실행
