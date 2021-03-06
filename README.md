
# DBT Daily Assignment;


### Aug 24
      Select statement
      1. Display table structure for table employees and departments. 2. Check all table names available in your schema.
      3. Display all employees data
      4. Display all data from departments table
      5. Display employee_id, last_name,annual salary for all employees also display column heading as "Annual Salary"
      6. Display unique job code from employees table
      7. Write a query to display commission value for employees who earn it and 'NULL' should be displayed for employees who do not earn,rename column as "comm"
      8. Write a query to display employee's full name seperated by space.
      9. Write a query to display last_name and job_id as follows eg: King is working as manager and name the column as "Employee Details"
      10. Display only unique departments from employees table
      11. Display unique departments and employee_id,last_name,salary working in those departments
      11. Display unique departments and employee_id,last_name,salary working in those departments
      

      Restricting and Sorting Data
      1. Display emp_id,name,salary,commission,department_id for department 80 and rename column as Emp#,Employee,Salary,Comm respectively
      2. Display last_name and first_name for employees having last_name as king
      3. Display employee details hired on 23-mar-1998
      4. Display name and salary for employees earning more than 15000 of salary

### Aug 25
      1. Display last_name for employees starting with capital 'A'
      2. Displayfirst_name for employees containing letter 'e'
      3. Display names for emloyees whose name ends with 's'
      4. Display names for employees hired in month of March
      5. Dislay name, salary, job_id for employees having 'REP' in their job_id
      6. Display names for employees containing 2nd last letter 'a' in last_name
      7. Display names for employees containing 'a' and 'e' both in the full_name
      8. Display name, salary,commission for those employees who do not earn commission
      9. Display name, salary for employees having salary not in range 5000 to 12000
      10. Create a report to display last_name,job_id ,hire_date for employees Matos and Taylor in the same query .Sort data in ascending order by hire_date
      11. Dislplay data for employees working in department 20 or 50 and sort in alphabetical order of name
      12. Display details for employees who earns between 5000 to 17000 and work in department 20 or 50,Sort data in descending order of salary
      13. Write a query to display emp_id,last_name,salary for employees working under department which users prompt's while executing query 14. Write a query to display emp_id,last_name,salary for employees earning salary specified by user and sort data on the basis of user specified column.
      15. Display salary for employees whose salary is not equal to 2500 or 3500 or 7000
      16. Try out same queries (wherever applicable)with substitution variable.
      

### Aug 27
            1. Try executing round() and truc() for dates of your choice instead of sysdate
            2. Display emp_id,last_name,salary in following format eg: 100 King $24,000 (having $ and comma)
            3. Display hire_date of employees in following format eg: 17th of January in 1997
            4. Calculate annual salary (12*salary*commission) for employees wheather he earns commission or not.
            5. Write a query to display empid ,annual salary for all employees also next column should describe 'sal+comm' or 'sal' accordingly. Eg: 179 sal+comm 7440
            6. Write a query where organization wants to give a salary increment of $2,000 for all employees.And who get commission, the query should compute the incremented salary added to the commission amount.
            7. Create a report that produces the following for each employee: <employee last name> earns <salary> monthly but wants <3 times of current salary.>. Label the column Dream Salaries.
            8. Display each employee?s last name, hire date, and salary review date, which is the first Monday after six months of service. Label the column REVIEW. Format the dates to appear in the format similar to ?Monday, the Thirty-First of July, 2000.?
            9. Display the last name, hire date, and day of the week on which the employee started. Label the column DAY. Order the results by the day of the week, starting with Monday.
            10. Create a query that displays the employees? last names and commission amounts. If an employee does not earn commission, show ?No Commission.? Label the column COMM.
            11. Using the DECODE function, write a query that displays the grade of all employees based on the value of the column JOB_ID, using the following data:

                  job AD_PRES A
            ST_MAN B IT_PROG C

   ### Aug 26
         1. First Rewrite /practice all demo queries taught in session.
      2. Display full names of employees separated by space and initial letter of every word should be in capital, rename column as "Name"
      3. Display last_name in capital letters
      4. Generate login_id for employees consisting upto 5 characters of first_name and initial letter first last_name and underscore as a separator
      5. Display system date through query
      6. Display emp_id,last_name, annual salary rounded to nearest whole number .
      7. Write query to display hike in salary by 15.5% and round to nearest whole number
      8. Modify above query in different script file where you should also display revised salary i.e. old salary subtracted from new salary
      9. Display last_name for employees where starting character will be prompted by user and the case should not affect to output
      10. Display last_name and length of last-name whose names start with 'J' or 'H' or 'T'. Sort data in alphabetical order of names
      11. HR department wants to check for how many months every employee has worked with the organization sort data by order of months. (Hint: calculate months between todays date and hire_date)
      12. Display last_name of employee and indicate the amount of their salaries with asterisks. Each asterisk signifies a thousand dollars sort data in desending order of salary. Eg: king earns 24,000 so 24 asterisks should be displayed and not the salary
      
      
   ### Aug 28
         1. First Rewrite /practice all demo queries taught in session. 2. Display maximum salary from department 20
      3. Display the oldest hire_date from employees
      4. Find out the correct average salary
      5. Display count of employees earning commission
      6. Display department_id,maximum salary department-wise
      7. Display department_id,minimum salary for those departments whose min sal is less than 7000
      8. Write a query to display the number of people with the same job. (count jobwise)
      9. Re-write the above query where user is prompted for job_id. (eg. : "REP" if entered they display all emp with job_id having REP
      10. Find the difference between the highest and lowest salaries. Label the column DIFFERENCE
      11. Create a report to display the manager number and the salary of the lowest-paid employee for that manager. Exclude anyone whose manager is not known. Exclude any groups where the minimum salary is $6,000 or less. Sort the output in descending order of salary.
      12. Create a query to display the total number of employees hired in 1995, 1996, 1997, and 1998. Create appropriate column headings.


### Aug 29
      1. Write a query for the HR department to produce the addresses of all the departments. Use the LOCATIONS and
      COUNTRIES tables. Show the location ID, street address, city, state or province, and country in the output. Use a NATURAL JOIN to produce the results
      2. Write a query to display the last name, department number, and department name for all the employees.
      3. Display the last name, job, department number, and the department name for all employees who work in Toronto (use table LOCATIONS)
      4. Create a report to display employees? last name and employee number along with their manager?s last name and manager number. Label the columns Employee, Emp#, Manager, and Mgr#, respectively
      5. Modify query no. 4 to display all employees including King, who has no manager. Order the results by the employee number.
      6. Create a report for the HR department that displays employee last names, department numbers, and all the employees who work in the same department as a given employee prompted on screen.
      7. Create a query that displays the name, job, department name, salary, and grade for all employees. (use table SALGRADE)
      8. The HR department needs to find the names and hire dates of all the employees who were hired before their managers, along with their managers? names and hire dates.
      9. Display id,city,state for city 'Manchester' (use table states and stations) Describe and check the column headings 10. Display id,city,state and location name for city .(use station and location tables)
      11. Display stateid,statename its city and location
      12. Display custid,name,orderdate,shipping date and total amount of order (use table customer and ord)
      13. Display itemid its actualprice and product description. (use table item and product)
      14. Display all orders with orderdate and total for cuutomer JOCKSPORTS (use table customer and ord)
      
### Aug 31
      1. The HR department wants to determine the names of all the employees who were hired after Davies. Create a query to display the name and hire date of any employee hired after employee Davies.
      2. Display employee details who earns more than employee 'Abel'
      3. Display empid,last_name,salary,job for emloyees working in department same as 'Taylor' and earns less than him 4. Display employee details who earns minimum salary
      5. Display department-wise dept_id,salary for those departments whose max salary is more than 10000
      6. Display empid,dep-id,salary for those employees who earn maximum in his department. Eg: king earns highest salary ($24000) in his department(90)
      7. display second highest salary
      8. Display duplicate employee names
      9. Display n^th highest salary where value of 'n' is given by user (i.e if user enters 3 then, 3 highest salaries should be displayed)
      10. The HR department needs a query that prompts the user for an employee last name. The query then displays the last name and hire date of any employee in the same department as the employee whose name they supply (excluding that employee). For example, if the user enters Zlotkey, find all employees who work with Zlotkey (excluding Zlotkey).
      11. Create a report that displays the employee number, last name, and salary of all employees who earn more than the average salary. Sort the results in order of ascending salary.
      12. Write a query that displays the employee number and last name of all employees who work in a department with any employee whose last name contains the letter ?u.?
      13. The HR department needs a report that displays the last name, department number, and job ID of all employees whose department location ID is 1700.
      14. Create a report for HR that displays the last name and salary of every employee who reports to King.
      15. Create a report for HR that displays the department number, last name, and job ID for every employee in the Executive department.
      16. Display only stateid and statename for location under location Toronto
      17. Display statename for city ''Fredericktown"
      18. Write a query to display the last name, department number, and salary of any employee whose department number and salary both match the department number and salary of any employee who earns a commission
      19. Display the last name, department name, and salary of any employee whose salary and commission match the salary and commission of any employee l ocated in location ID 1700
      20. Create a query to display the last name, hire date, and salary for all employees who have the same salary and commission as Kochhar. Note: Do not display Kochhar in the result set.
      21. Create a query to display the employees who earn a salary that is higher than the salary of all of the sales managers (JOB_ID = 'SA_MAN'). Sort the results on salary from highest to lowest
      22. Display the details of the employee ID, last name, and department ID of those employees who live in cities whose name begins with T.
      23. Write a query to find all employees who earn more than the average salary in their departments. Display last name, salary, department ID, and the average salary for the department. Sort by average salary. Use aliases for the columns retrieved by the query as shown in the sample output.
      24. Write a query to display the employee ID, last names, and department names of all employees. Note: Use a scalar subquery to retrieve the department name in the SELECT statement.
      25. Write a query to display the last names of the employees who have one or more coworkers in their departments with later hire dates but higher salaries.

### Sep 1

      Set operators
      1. The HR department needs a list of department IDs for departments that do not contain the job ID ST_CLERK. Use the set operators to create this report.
      2. The HR department needs a list of countries that have no departments located in them. Display the country ID and the name of the countries.
      3. Produce a list of jobs for departments 10, 50, and 20. Display the job ID and department ID by using the set operators.
      4. Create a report that lists the employee IDs and job IDs of those employees who currently have a job title that is the same as their job title when they were initially hired by the company (that is, they changed jobs but have now gone back to doing their original job).
      5. The HR department needs a report with the following specifications:
      Last name and department ID of all employees from the EMPLOYEES table, regardless of whether or not they belong to a department
      Department ID and department name of all departments from the DEPARTMENTS table, regardless of whether or not they have employees working in them Write a single query to accomplish this.

### Sep 2
      1. Run the statement to build the MY_EMPLOYEE table to be used for the lab.
      2. "Add the first row of data to the MY_EMPLOYEE table . Do not list the columns in the INSERT clause.Make the data additions permanent."
      3. Populate the MY_EMPLOYEE table with the second row of sample data from the preceding list. This time, list the columns explicitly in the INSERT clause
      4. Write an INSERT statement in a text file named loademp.sql to load rows into the MY_EMPLOYEE table. Concatenate the first letter of the first name and the f irst seven characters of the last name to produce the user ID.
      5. Change the last name of employee 3 to Drexler
      6. Change the salary to 1000 for all employees with a salary less t han 900.Verify your changes to the table.
      7. Delete an employee from the MY_EMPLOYEE table. Prompt user on screen for first_name
      8. Try all these:: Mark an intermediate point in the processing of the transaction. Empty the entire table.Confirm that the table is empty.
      9. Discard the most recent DELETE operation without discarding the earlier INSERT operation.Confirm that the new row is still intact

### Sep 3

      1. Create table copy_emp same as employees table
      2. Populate the DEPT table with data from the DEPARTMENTS table. Include only columns that you need
      3. Create table EMP and add all necessary constraints.Include only the EMPLOYEE_ID, FIRST_NAME, LAST_NAME, SALARY, and DEPARTMENT_ID columns. Name the columns in your new table ID, FIRST_NAME, LAST_NAME, SALARY , and DEPT_ID, respectively.
      4. Truncate table EMP
      5. Drop the EMP table
      6. Now again create table EMP.Add a table-level PRIMARY KEY constraint to the EMP table on the ID column. The constraint should be named at creation. Name the constraint my_emp_id_pk.
      7. Create a PRIMARY KEY constraint to the DEPT table using the ID column. The constraint should be named at creation. Name the constraint my_deptid_pk.
      8. Modify the EMP table to allow for longer employee last names. Confirm your mod ification.
      9. Confirm that both the DEPT and EMP tables are stored in the data dictionary. (Hint: USER_TABLES)
      10. Drop the FIRST_NAME column from the EMP table. Confirm your modification by checking the description of the table.
      11. Add a column DEPT_ID to the EMP table. Add a foreign key reference on the EMP table that ensures that the employee is not assigned to a nonexistent depar tment. Name the constraint my_emp_dept_id_fk.
      12. Confirm that the constraints were added by querying the USER_CONSTRAINTS view. Note the types and names of the constraints.
      13. Display the object names and types from the USER_OBJECTS data dictionary view for the EMP and DEPT tables. Notice that the new tables and a new index were created
      14. Modify the EMP table. Add a COMMISSION column of NUMBER data type, precision 2, scale 2. Add a constraint to the commission column that ensures that a co mmission value is greater than zero


 ### Sep 4

            1. Create a view called EMPLOYEES_VU based on the employee numbers, employee names, and department numbers from the EMPLOYEES table. Change the heading for the employee name to EMPLOYEE.Display the contents of the EMPLOYEES_VU view. 2. Select the view name and text from the USER_VIEWS data dictionary view.
            3. Using your EMPLOYEES_VU view, enter a query to display all employee names and department numbers.
            4. Create a view named DEPT50 that contains the employee numbers, employee last names, and department numbers for all employees in department 50. Label the view columns EMPNO, EMPLOYEE, and DEPTNO. Do not allow an employee to be reassigned to another department through the view
            5. Create a view called SALARY_VU based on the employee last names, department names, salaries, and salary grades for all employees. Use the EMPLOYEES, DEPARTMENTS, and JOB_GRADES tables. Label the columns Employee, Department, Salary, and Grade, respectively. 


### Sep 5
            1. Create a sequence to be used with the primary key column of the DEPT table. The sequence should start at 200 and have a maximum value of 1000. Have your sequence increment by ten numbers. Name the sequence DEPT_ID_SEQ
            2. Write a query in a script to display the following information about your sequences: sequence name, maximum value, increment size, and last number. Name the script lab13_2.sql. Run the statement in your script
            3. Write a script to insert two rows into the DEPT table. Name your script lab13_3.sql. Be sure to use the sequence that you created for the ID column. Add two departments named Education and Administration. Confirm your additions. Run the commands in your script
            4. Display the indexes and uniqueness that exist in the data dictionary for the EMP table.
            5. Create a nonunique index on the foreign key column (DEPT_ID) in the EMP table.


 ### Sep 7
            1. Create and execute a simple anonymous block that outputs ?Hello World.?
            2. Create and execute a simple anonymous block to display highest salary among-st employees
            3. Create PL/SQL block to display details of the employee who earns highest salary
            4. Create PL/SQL block to display the details for user entered employee_id
            5. Create PL/SQL block to display details nos. 1 to 10
            6. Create block to accept no. from user and check if it is Prime or Not and display message accordingly
            7. Create PL/SQL block to accept no. from user and check if it is armstrong no. or not
            8. Create PL/SQL block to accept radius and calculate and display area and circumference of circle
            9. Create PL/SQL block to accept no. and check if it is even or odd
            10. Create PL/SQL block to display details of the employee who do not have manager.
            Cursors
            1. Create PL/SQL block to display details of employees King
            2. Create PL/SQL block to display all duplicate names from employees 3. Create PL/SQL block to accept department_id from user and display detail of employees working under this department.
            4. Create PL/SQL block to display highest salary from each department 5. Create PL/SQL block to display details of employees earning highest salary in their department
            6. Create PL/SQL block to display all employees working in Toronto
            7. Create PL/SQL block to display employees hired in month of Aug
            8. Display eid, full name, salary, job_id, dept_name, city of employees for user entered city.
            9. Create PL/SQL block to display employees who have changed their job atleast once
            10. Create PL/SQL block to details of employees earning salary in range 10000 to 20000


 ### Sep 8


            1.Write a function which returns basic salary of an employee (DA+HRA+ALLOWANCE). Later use the above function to calculate total salary of employees
            2.Write a function which returns max salary of user entered department_id. Use this function to display max salary and its department details
            3.Create and compile a function called GET_JOB to return a job title.
            Create a VARCHAR2 host variable called TITLE, allowing a length of 35 characters. Invoke the function with SA_REP job ID to return the value in the host variable. Print the host variable to view the result.
            4.Create a function called GET_ANNUAL_COMP to return the annual salary computed from an employee?s monthly salary and commission passed as parameters.
            Develop and store the GET_ANNUAL_COMP function, accepting parameter values for monthly salary and commission. Either or both values passed can be NULL, but the function should still return a non-NULL annual salary. Use the following basic formula to calculate the annual salary:
            (salary*12) + (commission_pct*salary*12)
            Use the function in a SELECT statement against the EMPLOYEES table for employees in department 30.

            1.Create a procedure called ADD_JOB to insert a new job into the JOBS table. Provide the ID and title of the job using two parameters.
            2.Create a procedure called UPD_JOB to update the job title. Provide the job ID and a new title using two parameters. Include the necessary exception handling if no update
            3.Create a procedure, ADD_EMPLOYEE, to insert a new employee into the EMPLOYEE table. The procedure should call a VALID_DEPTID function to check whether the department ID specified for the new employee exists in the DEPARTMENTS table.
            4.Create a procedure called GET_EMPLOYEE to query the EMPLOYEES table, retrieving the salary and job ID for an employee when provided with the employee ID. Execute the procedure using host variables for the two OUT parameters?one for
            the salary and the other for the job ID. Display the salary and job ID for employee ID 120.

 ### Sep 9

            1. The rows in the JOBS table store a minimum salary and a maximum salary allowed for different JOB_ID values. You are asked to write code to ensure that employees salaries fall within the range allowed for their job type, for insert and update
            operations.
            Write a procedure called CHECK_SALARY that accepts two parameters, one for
            an employee's job ID string and the other for the salary. The procedure uses the job ID to determine the minimum and maximum salary for the speci�ied job. If the salary parameter does not fall within the salary range of the job, inclusive of the minimum and maximum, then it should raise an application exception, with the message Invalid salary <sal>. Salaries for job <jobid> must be between<min> and <max>. Replace the various items in the message with values supplied
            by parameters and variables populated by queries. Save the �ile. [Use table Jobs]
            Create a trigger called CHECK_SALARY_TRG on the copy_emp table that �ires before an INSERT or UPDATE operation on each row. The trigger must call
            the CHECK_SALARY procedure to carry out the business logic. The trigger should pass the new job ID and salary to the procedure parameters.


            2. You are asked to prevent employees from being deleted during business hours. Write a statement trigger called DELETE_EMP_TRG on the employees_copy table to prevent rows from being deleted during weekday business hours, which are from 9:00 a.m. to 6:00 p.m. And day MON to FRI". Now, try deleting employee 205 from employees_copy table.
