# TechTestMoneyHub
Tech test at money hub for both postman tests and Javascript tests 

Tests to add Caroline Mcilhargey 

1.	AC1 I need to enter either an email or username 
a.	Enter a email =  pass 
b.	Enter username – Would add this test 
2.	AC2 I need to enter a password with a minimum character count of 6, and a maximum character count of 16
a.	Enter empty password – error -  / this is causing a failing test as cannot find error 
b.	Enter password with 5 characters – error /  (not tested) 
c.	Enter password with 6 characters – success  - / this would also cover the actions not assertions for 3 c , 4a, 5b and6 
d.	Enter password with 16 characters – success – not tested 
e.	Enter a password with 17 characters – success – not tested
3.	I must be prompted to re-enter my password, and the entered value must match the password
a.	User must be presented with re enter password 
b.	Password does not match – error 
c.	Password matches – success log in  - all one test which has been covered 
4.	I must be able to view the terms and conditions before I submit the form
a.	User can view terms and conditions  - covered in testing 
5.	I need to accept the terms and conditions before I can register
a.	User tries to submit without viewing terms and conditions – error – not covered 
b.	User can submit after terms and conditions have been met  - covered in test 
6.	When I click the register button, I am shown an alert.- Covered in testing 

Issues found on page –
 Username and password spelled wrong – this has been fixed 
The alert for the complete this field is not found in code. 
There is no change to page when registered
The error is not displayed when passwords don’t match 




