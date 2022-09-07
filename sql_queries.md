create table Employees(
id int auto_increment primary key,
name varchar(20) not null,
salary int not null,
number int unique not null,
age int not null,
nationality varchar(30)
)



insert into Employees (name,salary,number,age,nationality)
values ('Wad',3400,1855,34,'Japan')

select * from Employees

select * from Employees
where number=3413;

select * from Employees
where salary>2500;

select * from Employees
where name like'A%';

select * from Employees
where nationality in ('China','Japan','Russia','Korea');

select * from Employees
where age between 30 and 50;

select * from Employees
where name='Wad' and nationality='Japan';

select * from Employees
where age>30 and number=7560 or number=1853;

delete from Employees
where number=4014;

delete from Employees;