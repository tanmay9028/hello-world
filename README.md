# hello-world
Mysql commands to create company database
create database compony;
show databases;
use databases;
create table employee(eid int primary key not null,ename varchar(20) not null,edept int,salary int);
desc employee;
insert employee values(10,"AAA",201,25000);
insert employee values(11,"BBB",202,35000);
insert employee values(12,"CCC",203,45000);
