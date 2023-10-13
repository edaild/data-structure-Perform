# data-structure-Perform

![image](https://github.com/edaild/data-structure-Perform/assets/109999749/3a3b9ad1-36c8-4c51-a7fe-4425663e01e3)

## SQL code
```
mysql -u root -p
create user'user'@'localhost'identified by '12345';
greant all privileges on *.* to 'user'@'localhost';
quit
mysql -u user -p
12345
create database sungil
use sungil

create table publishing(
num int not null auto_increment,
title varchar(30),
isbn varchar(10),
publisher varchar(30),
price varchar(10),
primary key(num));

insert into publishing puvlishing(isbn, title , publisher, price) values ['A001','자료구조','가나출판','10000')
insert into publishing puvlishing(isbn, title , publisher, price) values ['A002','데이터베이스','다라출판','5000')
insert into publishing puvlishing(isbn, title , publisher, price) values ['A003','웹디자인','마바출판','500')

select * from publishing whare title like '데이터%';

update publishing set title='자료' where title = '자료구조'

delect publishing where isbn='A003';


```

