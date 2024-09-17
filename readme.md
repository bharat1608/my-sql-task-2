# DB Model - GUVI Zen Class

## MySQL - Task 02

### 1. Create Database:
```sql
Create database zenclass;

1.Courses table:
create table courses(
-> id int primary key,
-> courseName varchar(255),
-> description text
-> );

2.Batches table:
create table batches(
-> id int primary key,
-> batchName varchar(255),
-> );

3.Mentors table:
create table mentors(
-> id int primary key,
-> name varchar(255),
-> );

4.Students table:
create table students(
-> id int primary key,
-> studentname varchar(255),
-> );

5.Tasks table:
create table tasks(
-> id int primary key,
-> taskname varchar(255),
-> status varchar(255),
-> assignedDate date,
-> submittedDate
-> );



6.Class table:
create table class(
-> id int primary key,
-> batchId int,
-> studentId int,
-> courseId int,
-> mentorId int,
-> taskId int
-> );

