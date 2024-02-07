REST API using ASP.NET Core, Entity Framework Core and Code First Pattern##


Technologies used:
• ASP.NET Core • Entity Framework Core • Entity Framework Migrations – Code First • Repository pattern

https://github.com/Souhail-Elmokadem/gestion-films-asp-.net-7/assets/102615382/ed7efaa2-eefe-48e6-8e5f-a5732460397c



1. Installing .NET Core
To install .NET Core please follow the steps on the official web site https://www.microsoft.com/net/core#windowsvs2015

2. Opening project
-Open the solution in VS 2022

-Open Package Manager Console on the project by going to: Tools > Nuget Package Manager > Package Manager Console

-On the start up class modify the database connection string (connection) to reflect your database environment

-Run the following commands (they will create the database schema on your database environment):

	dotnet ef migrations add MyMigration

	dotnet ef database update
3. Build and Run
You could test the API using POSTMAN which can be downloaded from here: https://www.getpostman.com/
