# JPA TUTORIAL 📚📖💡


JPA를 사용한 코드 실습 내용을 기록하는 repo입니다.
코드의 추가적 코멘트가 필요하다면 [TIL](https://github.com/AhKong/TIL) 에 commit 합니다.






### 2021.02.14
Join 하여 원하는 데이터 조회 실습 

사용한 테이블 쿼리문
```
create table class (
   id int(11) not null primary key,
   name varchar(100) not null,
   addr varchar(100) not null,
   created_at datetime default now()
);

create table student(
  id int(11) not null primary key,
  class_id int(11) not null, 
  name varchar(100) not null,
  age int(11) not null,
  created_at datetime default now()
);
```
