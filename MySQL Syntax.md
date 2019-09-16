### CRUD
데이터 베이스가 가지고 있는 4가지 주요 작업

1. Create
2. Read
3. Update
4. Delete

------

### Mysql 이용

```
1. root 계정으로 접속 : mysql -uroot -p
2. DB 생성 : ex) table name-test
   create database test;
3. user 생성 및 권한 부여 : ex) user-aldrn, pw-1111 
   create user 'aldrn'@'localhost' identified by '1111';
   grant all privileges on test.* to 'aldrn'@'localhost';
4. 권한 확인 : show grants for 'User 이름'@'localhost';
5. 바로 적용 : flush privileges;

```


### db

```
- test db 생성 : CREATE DATABASE test;
- db 보기 : SHOW DATABASES; 
- test db 선택 : USE test;
- test db 삭제 : DROP DATABASE users;
```

### table
```
- table 생성 : CREATE TABLE info (id INT(11) NOT NULL)
- table 보기 : SHOW TABLES;
- info table 정보 보기 : DESK info;
```
