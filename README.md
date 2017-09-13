# my-SQL
the user
select * from tablename;查看
delete from tablename where condition;删除
update tablename set col_name=value,col_name=value where condition; 更新
insert into tablename(col_name,col_name) values(value,value); 插入
show databases;查看数据库
use databasename;使用数据库
create table tablename(col_name not null auto_increment,col_name type default,primary key(col_name));创建表
show tables;查看数据库下的所有表
select col_name,col_name from tablename;从表中查看某几列的数据
select * from tablename limit 4;查询前四条数据
select * from tablename limit 4，5;排除前四条数据后，查找接下来的5条数据
select * from tablename where id>100;查找id>100的所有表数据
select * from tablename order by id;通过id进行排序
select * from tablename order by id desc;通过id进行倒序排序
select * from tablename order by id，col_name;先通过id排序，然后再通过col_name排序




