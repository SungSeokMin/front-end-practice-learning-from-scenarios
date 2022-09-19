# 12shop PoC

### 1. Docker 설치

[Docker 설치하기](https://www.docker.com/)

```
// mysql 이미지 생성
docker pull mysql:latest

// mysql container 생성
docker run --mysql-container -e MYSQL_ROOT_PASSWORD=1234 -d -p 3306:3306 mysql
```

### 2. 데이터베이스 생성

```sql
CREATE DATABASE 12shop DEFAULT CHARACTER SET = 'utf8mb4';
```
