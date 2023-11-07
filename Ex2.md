# EX 2 Data Manipulation Language (DML) Commands and built in functions in SQL
## DATE:10/08/2023
## AIM:
To create a manager database and execute DML queries using SQL.


## DML(Data Manipulation Language)
<div align="justify">
The SQL commands that deal with the manipulation of data present in the database belong to DML or Data Manipulation Language and this includes most of the SQL statements. It is the component of the SQL statement that controls access to data and to the database. Basically, DCL statements are grouped with DML statements.
</div>

## List of DML commands: 
<div align="justify">
INSERT: It is used to insert data into a table.<br>
UPDATE: It is used to update existing data within a table.<br>
DELETE: It is used to delete records from a database table.<br>
</div>

## Create the table as given below:
```sql
create table manager(enumber number(6),ename char(15),salary number(5),commission number(4),annualsalary number(7),Hiredate date,designation char(10),deptno number(2),reporting char(10));
```
## insert the following values into the table
```sql
insert into manager values(7369,'Dharsan',2500,500,30000,'30-June-81','clerk',10,'John');
insert into manager values(7839,'Subu',3000,400,36000,'1-Jul-82','manager',null,'James');
insert into manager values(7934,'Aadhi',3500,300,42000,'1-May-82','manager',30,NULL);
insert into manager values(7788,'Vikash',4000,0,48000,'12-Aug-82','clerk',50,'Bond');
```

### Q1) Update all the records of manager table by increasing 10% of their salary as bonus.

### QUERY:
![280691507-c0035606-8e37-4791-b48e-2fd34d69f944](https://github.com/MaithreyanDinakaran/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119104032/95a5140a-6af8-4794-b81c-55837e748b98)


### OUTPUT:

![280691554-0b902c3e-d7ae-42a5-b4fc-d06943094b37](https://github.com/MaithreyanDinakaran/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119104032/48a87c89-7452-41d1-af23-699002016be2)

### Q2) Delete the records from manager table where the salary less than 2750.


### QUERY:

![280691674-af5a5e05-23e5-4157-9310-a3a67b817a29](https://github.com/MaithreyanDinakaran/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119104032/24c18022-fe3b-46fd-a168-fc94308aee39)


### OUTPUT:

![280691835-ca9586e9-ef9e-48fa-9ac0-0d53bef7e545](https://github.com/MaithreyanDinakaran/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119104032/fd1970ff-9932-4999-92f8-aa004107ccb0)

### Q3) Display each name of the employee as “Name” and annual salary as “Annual Salary” (Note: Salary in emp table is the monthly salary)


### QUERY:

![280691881-68d421b6-49c7-4e4c-b853-a63afd3f3927](https://github.com/MaithreyanDinakaran/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119104032/874872e0-dc97-4e91-9e78-5ba61ca272b5)


### OUTPUT:

![280691906-9dbe920d-eef1-4a71-a660-020a8382e00c](https://github.com/MaithreyanDinakaran/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119104032/ecc6ccd7-a625-4888-a66c-11ada5ca090f)

### Q5)	List the names of Clerks from emp table.


### QUERY:

![280691943-59d03b94-48b5-4df8-be9a-5749d9839b84](https://github.com/MaithreyanDinakaran/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119104032/fc381401-303c-4324-91a7-c8750e048afc)


### OUTPUT:

![280691970-beca32ac-9ddb-4df2-bffe-c5904e6cf4de](https://github.com/MaithreyanDinakaran/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119104032/ed67c600-878f-479b-abb4-ad8f1cc3dd7b)


### Q6)	List the names of employee who are not Managers.


### QUERY:

![280692016-589bc4e0-7695-4eb2-893a-cb4c1350b64a](https://github.com/MaithreyanDinakaran/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119104032/559bc873-4de2-434a-91f5-2d94256eb969)


### OUTPUT:

![280692039-f7acbce8-6e7d-4fbb-af52-5acc26b5f699](https://github.com/MaithreyanDinakaran/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119104032/2ad84f87-6298-45a3-b291-4b4bc4fb9077)


### Q7)	List the names of employees not eligible for commission.


### QUERY:

![280692066-1a0327a7-6a62-47e9-86f2-9c738e5a4235](https://github.com/MaithreyanDinakaran/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119104032/40f1102f-a7e1-4c04-930e-e7e695324f1b)


### OUTPUT:

![280692109-f4a2b0d9-c8da-4323-bb08-15c0d965f8a2](https://github.com/MaithreyanDinakaran/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119104032/77f3ecee-f0a1-43fa-81b5-3e9c0a76e5de)


### Q8)	List employees whose name either start or end with ‘s’.


### QUERY:

![280692134-335da4d7-018b-4ca1-a57a-cdb4b57b4418](https://github.com/MaithreyanDinakaran/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119104032/11e4345d-1d7b-42d8-b154-94f4aaad2079)


### OUTPUT:

![280692206-502437b0-2399-4579-a557-60594dd696cf](https://github.com/MaithreyanDinakaran/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119104032/dc113a37-cf46-4c60-a325-7891816d2560)


### Q9) Sort emp table in ascending order by hire-date and list ename, job, deptno and hire-date.

### QUERY:

![280692232-3d3e6064-8b9c-4ade-912a-6338e4b38d41](https://github.com/MaithreyanDinakaran/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119104032/7a071607-f114-4586-9c98-b3cf9bd554b3)


### OUTPUT:

![280692263-93d86c37-76d3-477a-9869-f3c52938faf2](https://github.com/MaithreyanDinakaran/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119104032/0dac2a0a-5f4a-41c1-9fd3-5a070d92df4f)


### Q10) List the Details of Employees who have joined before 30 Sept 81.


### QUERY:

![280692454-5ee48983-aea1-40fd-afee-08b2953b25ec](https://github.com/MaithreyanDinakaran/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119104032/b198a704-21bf-4713-ac44-c5876db192db)


### OUTPUT:

![280692466-9aa9b0a2-a783-430d-bd98-389edfd01a1b](https://github.com/MaithreyanDinakaran/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119104032/1e66538b-92e5-4be4-b4e0-9439f9411738)


### Q11)	List ename, deptno and sal after sorting emp table in ascending order by deptno and then descending order by sal.


### QUERY:

![280692494-69e2a111-09de-4bea-baeb-bb407cf7ef47](https://github.com/MaithreyanDinakaran/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119104032/03e84c5f-df3c-43c8-8705-82cef8e6d0aa)


### OUTPUT:

![280692521-f9599776-6835-4d4f-a55a-57e4c876176e](https://github.com/MaithreyanDinakaran/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119104032/251aba97-6d8b-464f-beba-f2c2fb2fd6dc)


### Q12) List the names of employees not belonging to dept no 30,40 & 10


### QUERY:

![280692521-f9599776-6835-4d4f-a55a-57e4c876176e](https://github.com/MaithreyanDinakaran/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119104032/c4708a52-5d77-49c3-bbea-321712301bcb)


### OUTPUT:

![280692586-46c0225c-48d4-4a72-8793-af38eff1f02a](https://github.com/MaithreyanDinakaran/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119104032/1b471824-639c-402b-b3ac-81379226327e)

### Q13) Find number of rows in the table EMP

### QUERY:

![280692621-e27d184b-83ae-4fa3-b4d7-537748036d6d](https://github.com/MaithreyanDinakaran/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119104032/97fb2b7e-b9f1-4d98-9007-bb909ded9120)


### OUTPUT:

![280692638-b456cfaa-d6bd-4692-81f2-f8458278cb05](https://github.com/MaithreyanDinakaran/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119104032/30f0d4b7-91f5-4cd4-bae1-f0e7de368eb4)


### Q14) Find maximum, minimum and average salary in EMP table.

### QUERY:

![280692665-9a2745e9-c67f-4532-ae99-1f686381c9a3](https://github.com/MaithreyanDinakaran/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119104032/46cf1624-eda4-42f4-a780-1186d3000aba)


### OUTPUT:


![280692684-e8fb67f1-4151-454b-9447-3481910b3f56](https://github.com/MaithreyanDinakaran/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119104032/e9f7a8a6-364c-4257-8ddd-1a8cc5f8712c)


### Q15) List the jobs and number of employees in each job. The result should be in the descending order of the number of employees.

### QUERY:

![280692726-ac0f8772-861c-4648-9c21-c08ede389ecd](https://github.com/MaithreyanDinakaran/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119104032/75e64c8b-4967-4fd4-86a1-338a7eebae0a)


### OUTPUT:

![280692755-f7664cf4-5a48-4d0b-b59a-76af6216f386](https://github.com/MaithreyanDinakaran/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/119104032/c57decc9-0114-4c52-895b-b1e936e1f393)

## RESULT:
Thus,the data manipulation language and data control language commands are executed.
