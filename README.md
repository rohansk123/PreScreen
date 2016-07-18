Microsoft Full Stack Applicant Prescreen
========================================
Fork this project and send us a pull request completing the following Visual Studio solution:

Add a SQL Database Project to the solution
------------------------------------------

Employing LocalDB, create a database called Database1 and then design a simple user account table with primary key Id, a UserName field, an Email field, and a Password field.

Add a web application project to the solution
---------------------------------------------

This web app should minimally provide all four aspects of a simple CRUD implementation to manage user accounts in the LocalDB user account table.

The web application must demonstrably employ the LATEST of these NuGet packages:

* Entity Framework 6

* JQuery

* Bootstrap

* Newtonsoft.Json

Add an ADO.Net Entity Data Model to the web application
-------------------------------------------------------

 * Your choice of Database-first or Code-first
 
Employing the LocalDB instance where your database resides, this model should expose the Database1 user account table and provide all of the projects database management needs through Linq-To-Entities.

Overall implementation should minimally ensure the following policies
---------------------------------------------------------------------

* Each Id is unqiue.

* Each UserName is unique.

* Each Email is unique.

* Passwords should be stored as one-way MD5 Hash.


**NOTE - The entire solution must build without error.**

Working Site
------------

Finally, in your Pull Request description or comments, supply a url to a working version of your web application (hosted free at AppHarbor or Azure is fine).

Hello
