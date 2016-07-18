# PreScreen
Microsoft full stack applicant prescreen

Fork this project and send us a pull request completing the following Visual Studio solution:

Add a SQL Database Project to the solution.
Employing LocalDB, design a simple user account table with primary key Id, a UserName field, an Email field, and a Password field.

Add a web application project to the solution that provides all four aspects of a simple CRUD implementation to manage user accounts in the LocalDB user account table.

The web application must demonstrably employ the LATEST of these NuGet packages:

Entity Framework 6
JQuery
Bootstrap
Newtonsoft.Json

Using EF6, expose the LocalDB user account table to Linq To Entities for your database management needs.

The overall implementation of the solution should minimally ensure the following policies:

Each Id is unqiue.
Each UserName is unique.
Each Email is unique.
Passwords should be stored as one-way MD5 Hash.


The entire solution must build successfully.

