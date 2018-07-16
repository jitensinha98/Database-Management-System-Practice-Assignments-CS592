# Database creation guidelines

Open up windows start menu and start **SQL COMMANDLINE**.

## Execute the following commands 

```
connect sys/oracle as sysdba;
```
This would set the path of database storage to localhost.

```
create table Emp(empno varchar2(10),empname varchar2(10),designation varchar2(10),salary number(10));
```
Thsi would create a database named 'Emp' and will have the following fields-empno,empname,designation,salary.

```
desc Emp
```
This would show the datatype of the fields.
```
insert into Emp values('&empno','&empname','&designation','&salary');
```
This would take inputs for the fields in the database.

```
/
```
Executing this would execute the last command and hence can be used to insert multiple values without having to type the entire code.
```
select * from Emp
```
This would display the database named Emp.

## Screenshots

![screenshot 1](https://user-images.githubusercontent.com/36096530/42769574-1ec1420c-8940-11e8-8e2f-552dde2f49c6.png)
![screenshot 2](https://user-images.githubusercontent.com/36096530/42769579-284dce26-8940-11e8-8a41-798889dd5360.png)
