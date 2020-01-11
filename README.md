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

    CREATE TABLE topic(
        id INT(11) NOT NULL AUTO_INCREMENT,
        title VARCHAR(100) NOT NULL,
        description TEXT NULL,
        created DATETIME NOT NULL,
        author VARCHAR(30) NULL,
        profile VARCHAR(100) NULL,
        PRIMARY KEY(id)
    )

테이블 생성, length는 보통 11을 사용함.

NOT NULL : 값이 없는것을 허용하지 않음.

AUTO_INCREAMENT : 데이터가 추가될때 자동으로 값이 1씩 증가한다.

NULL : 값이 없는것을 허용한다.

PRIMARY KEY(id) : 메인 키를 알려준다
