============================================================================================
Please follow instructions steps to run my C# projects (BookStore_Proj)
============================================================================================

1. Since my C# project is implemented with MySQL database, you need to import MySQL dump file namely (bookstore_db.sql) under "Database file" folder that including in my project zip file 

2. Open the MySQL workbench and click the "Server" tab on navigation bar and choose "Data Import" option.

3. Please select the "Import from self-contained file" option and click browse option and browse my target dump file namely (bookstore_db.sql) which is located in my project zip folder.

4. And then, click on "New.." to create schema and type as "bookstore_db", and click OK.

5. After that, please select the "Import Process" tab and click the "Start Import" button.

6. Your import status will be completed after your SQL dump file importing.

7. Since this project is implemented based on MySql database server, you might change the Uid and Pwd for my database when running my project. 
   If this needs, you only need to make chages only for "DatabaseConnection.cs" class file of my program.

	  public static MySqlConnection dataSource()
  	   {
 
 	     cn = new MySqlConnection("Server=localhost;Database=homeappliancerental_db;Uid=root;Pwd=root;");
     
     	     return cn; 
  
  	    }


================================================================================================



Here is the testing accounts for the Admin and Customer for my system.
*********************************************************************

For Admin Account
=================
Username: Admin
Password: Admin1234

For User Accounts: Customer
=======================
Username: Kyaw
Password: Kyaw1234


___________________________________________________________________________________________

Note:   If you want to register as an admin account, the registeration permission password is "PermitAdmin@123".







_________________________________________________________________________________End!!!!!!_______________________________________________________________________________________________________________



 