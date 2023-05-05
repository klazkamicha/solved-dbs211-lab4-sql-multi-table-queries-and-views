Download Link: https://assignmentchef.com/product/solved-dbs211-lab4-sql-multi-table-queries-and-views
<br>
The purpose of this lab is to introduce students to querying data from multiple tables.  Relationships are used in relational databases to reduce redundant and repetitive data, but it is necessary to reconnect these tables when extracting data and obtaining information.  Student will be able to:

<ul>

 <li>produce query results containing data from multiple tables using ANSI-92 joins and demonstrate their knowledge of inner, outer and full joins.</li>

 <li>To actively troubleshoot queries to handle potentially ambiguous fields across multiple tables through the use of aliases</li>

 <li>Students learn to create and modify views.</li>

</ul>

Submission:

<strong><em>Your submission will be a single text-based .</em></strong><strong><em>SQL file with the solutions provided. </em></strong>

Your submission needs to include a comment header block and be commented top clearly indicate the answers to each question.  Make sure every SQL statement terminates with a semicolon.

<strong>ALL questions must be answered using ANSI-92 JOINs unless otherwise stated</strong>.  ANSI-89 are obsolete and should not be used in new query derivations.

Tasks:

Select data from multiple tables

<ol>

 <li>Create a query that shows employee number, first name, last name, city, phone number and postal code for all employees in France.

  <ol>

   <li>Answer this question using an ANSI-89 Join</li>

   <li>Answer this question using an ANSI-92 Join</li>

  </ol></li>

</ol>




<ol start="2">

 <li>Create a query that displays all payments made by customers from Canada.

  <ol>

   <li>Sort the output by Customer Number.</li>

   <li>Only display the Customer Number, Customer Name, Payment Date and Amount.</li>

   <li>Make sure the date is displayed clearly to know what date it is. (i.e. what date is 02-04-19??? – Feb 4, 2019, April 2, 2019, April 19, 2002, ….)</li>

  </ol></li>

</ol>




<ol start="3">

 <li>Create a query that shows all USA customers who have not made a payment. Display only the customer number and customer name sorted by customer number.</li>

</ol>

Views and Joins

<ol start="4">

 <li>a) Create a view (<strong><em>vwCustomerOrder</em></strong>) to list all orders with the following data for all customers:</li>

</ol>

Customer Number, Order number, order date, product name, quantity ordered, and price for each product in every order.

<ol>

 <li>b) Write a statement to view the results of the view just created.</li>

 <li>Using the <strong><em>vwCustomerOrder</em></strong> view, display the order information for customer number 124. Sort the output based on order number and then order line number. (Yes, I know orderLineNumber is not in the view)</li>

 <li>Create a query that displays the customer number, first name, last name, phone, and credit limits for all customers who do not have any orders.</li>

 <li>Create a view (<strong><em>vwEmployeeManager</em></strong>) to display all information of all employees and the name and the last name of their managers if there is any manager that the employee reports to. Include all employees, including those who do not report to anyone.</li>

 <li>Modify the <strong><em>employee_manager</em></strong> view so the view returns only employee information for employees who have a manager. Do not DROP and recreate the view – modify it.</li>

</ol>

(Google is your friend).

<ol start="9">

 <li>Drop both <strong><em>customer_order</em></strong> and <strong><em>employee_manager</em></strong></li>

</ol>





