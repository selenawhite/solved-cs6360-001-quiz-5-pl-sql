Download Link: https://assignmentchef.com/product/solved-cs6360-001-quiz-5-pl-sql
<br>
<strong>Database Design </strong>

<strong> </strong>







<ol>

 <li>Write a trigger code that will be executed when a new employee is inserted into Employee table or salary of the employee is updated. It compares the employee salary with department manager’s salary and if it is higher than manager’s salary, raises an error. (Solution hint: To avoid mutating table problem, you can add Mng-Salary attribute to Department table or you can use compound triggers.)</li>

</ol>




<strong> </strong>

<ol start="2">

 <li>Write a stored procedure that will find all borrowers that has an overdue book for a given library branch. The procedure should insert values of book title, borrower name, borrower phone number and due date into OVERDUE table, which will be used for courtesy phone calls. The procedure should receive the Branch_id as an input parameter.</li>

</ol>




Use LIBRARY database schema given below.

Create an additional table named OVERDUE with following attributes:

Book_title, Borrower_name, Borrower_phone, Due_date.







<strong> </strong>

<ul>

 <li>Assume we add one additional attribute to BOOK_LOANS table with name “Return_date”. When a book is borrowed, Return_date takes initial value of NULL.</li>

</ul>










<strong>Deliverables:</strong> You can submit your solution as doc, pdf or sql file.