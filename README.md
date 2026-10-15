# Day-7-task
AGGREGATE FUNCTIONS

************
Write a query to find the total salary of all employees.
select sum(salary) from employees;
Write a query to find the average salary of employees.
select avg(salary) from employees;
Write a query to find the highest salary in the Employees table.
select max(salary) from employees;
Write a query to find the lowest salary in the Employees table.
select min(salary) from employees;
Write a query to count the total number of employees.

Write a query to count the number of employees in each department.
select count(*) from employees group by department;
Write a query to find the total salary paid in each department ,average salary of employees in each department,maximum salary in each department,minimum salary in each department.
select sum(salary) from employees group by department;
select avg(salary) from employees group by department;
select max(salary) from employees group by department;
select min(salary) from employees group by department;

Write a query to find the total sales for each product.
select sum(price) from amazon group by product_name;
Write a query to find the average marks of students in each subject.
select avg(marks)from students group by subject;
Write a query to display departments where the average salary is greater than 60,000.
select avg(salary) from employees group by department having avg(salary)>60000;
Write a query to display products whose total sales exceed 1,00,000.
select ORDERS from product group by productName having sum(price)>100000;
Write a query to find the total number of orders placed by each customer.
select customerID from orders group by customerId;
Write a query to find the customer who has placed the maximum number of orders.
select max(orderID)from orders group by customerId having max(orderID);
Write a query to find the total revenue generated each month.
Write a query to display classes having more than 30 students.
Write a query to find the highest marks scored in each subject.
Write a query to find the total quantity sold for each product where the total quantity is greater than 100.
select sum(quantity)from order_items group by productid having sum(quantity)>2;

***********



