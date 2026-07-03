# Perform SQL-injection
Perform SQL injection
 
 Task 1: Perform error-based SQL injection

•	 Click Windows Start and select Google Chrome.

<img width="582" height="789" alt="image" src="https://github.com/user-attachments/assets/732c2295-9103-4848-9d7d-748d019aeec7" />

At the top, click the Error-based SQL bookmark.

<img width="301" height="203" alt="image" src="https://github.com/user-attachments/assets/b2f7b600-8326-41da-a9c1-d56db1784fdd" />

The page outputs the admin's user ID, username, and password hash.

<img width="384" height="90" alt="image" src="https://github.com/user-attachments/assets/60177aa8-bb76-4307-aea0-f8e8ee1d7afd" />

In the Username box, replace admin with an apostrophe:

<img width="422" height="141" alt="image" src="https://github.com/user-attachments/assets/1499d3e2-a36f-4ee0-bf98-db11f358e7ca" />

// A database error happens due to improper error handling and indicates the Username input is not validated. An attacker can input malicious SQL and interact with the database.

<img width="999" height="87" alt="image" src="https://github.com/user-attachments/assets/6c4e7319-2bd0-466c-96a3-bed6aaa3475c" />

Enter the following to display all the available information in the database:

' or 1=1#

<img width="413" height="128" alt="image" src="https://github.com/user-attachments/assets/209341b6-dc62-4e8f-b420-1311cf65b21e" />

The page outputs every user's information.

<img width="403" height="305" alt="image" src="https://github.com/user-attachments/assets/06b13390-15d4-4ae1-b7bb-a2d23cf60408" />






