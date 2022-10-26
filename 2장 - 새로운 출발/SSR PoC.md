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

### 3. 더미 데이터 추가

```sql
insert into products (~) values (~);

insert into product-photos (~) values (~);
```

### 4. b2c server 및 cdn 서버 실행

### 5. rest client를 이용해 request 보내기

`rest client` 익스텐션 설치

```http
### Products
GET http://localhost:3000/products HTTP/1.1
```

```js
[
  {
    "id": "0021c4d6-9ad4-473a-a7d0-06158a26b646",
    "productName": "빈티지 일렉 기타",
    "price": 12,
    "detailDescription": "",
    "active": true,
    "photos": [
      {
        "id": "ece4fac7-afeb-4c2d-833f-cc5cdd8aa92d",
        "url": "01,ece4fac7-afeb-4c2d-833f-cc5cdd8aa92d.jpg",
        "contentType": "image/jpeg",
        "width": 1920,
        "height": 1134,
        "filesize": 0
      }
    ]
  },
  ...
]
```
