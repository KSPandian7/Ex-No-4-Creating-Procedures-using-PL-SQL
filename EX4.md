# Ex. No: 4 Creating Procedures using PL/SQL

### AIM: To create a procedure using PL/SQL.

### Steps:
1. Create employee table with following attributes (empid NUMBER, empname VARCHAR(10), dept VARCHAR(10),salary NUMBER);
2. Create a procedure named as insert_employee data.
3. Inside the procdure block, write the query for inserting the values into the employee table.
4. End the procedure.
5. Call the insert_employee data procedure to insert the values into the employee table.
6. Display the employee table

### Program:
```sql
DEVELOPED BY : KULASEKARAPANDIAN K
REGISTER NO : 212222240052
```
```sql
DELIMITER //
CREATE PROCEDURE insert_employee()
BEGIN
insert into employee(empid,empname,dept,salary)
values(101,'Kulasekarapandian','AIML',100000);
insert into employee(empid,empname,dept,salary)
values(102,'Aravind','AIDS',200000);
insert into employee(empid,empname,dept,salary)
values(103,'imthiyas','AIDS',300000);
COMMIT;
END // 


call insert_employee();

select * from employee
```
### Output:

#### Table:
![OUTPUT](/dbms4.png)


### Result:
THE PROGRAM HAS BEEN IMPLEMENTED SUCCESSFULLY.
