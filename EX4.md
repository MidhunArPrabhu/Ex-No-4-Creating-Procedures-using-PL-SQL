# Ex 4 Creating Procedures using PL/SQL

## AIM: 
To create a procedure using PL/SQL.

## STEPS:
- Create employee table with following attributes (empid NUMBER, empname VARCHAR(10), dept VARCHAR(10),salary NUMBER);
- Create a procedure named as insert_employee data.
- Inside the procdure block, write the query for inserting the values into the employee table.
- End the procedure.
- Call the insert_employee data procedure to insert the values into the employee table.
- Display the employee table

## PROGRAM :
```PY
create or replace procedure insert_employee_data AS
begin
insert into employee (empid,empname,dept,salary)
values (1,'john','HR',50000);
insert into employee (empid,empname,dept,salary)
values (2,'joe','IT',60000);
insert into employee (empid,empname,dept,salary)
values (3,'bob','Finance',55000);
commit;
end;
/
Procedure created.

begin
insert_employee_data;
end;
/

PL/SQL procedure successfully completed.
```
## Output:

![image](https://github.com/MidhunArPrabhu/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/118054670/2eff15c5-57bb-4fcc-9dc6-40b8b08f5705)

## RESULT :

Hence the procedure using pl/sql is created successfully.


