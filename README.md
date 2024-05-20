# CRUD-with-Drop-Down-List
ASP.NET Core MVC CRUD Operations with Dropdown List
This project demonstrates how to perform CRUD (Create, Read, Update, Delete) operations in an ASP.NET Core MVC web application, using a dropdown list for selecting related data. The project is built using Visual Studio 2022 and targets .NET 7.0. It showcases the implementation of two primary models: Category and Product. The Product model includes a foreign key relationship to the Category model, demonstrating how to handle relational data in a web application.

Key features of this project include:

ASP.NET Core MVC Framework: Utilizes the MVC design pattern to create a clean and maintainable code structure.
Entity Framework Core: Implements the Code First approach to define the database schema using C# classes and automatically migrate these schemas to a SQL Server database.
Dropdown List for Related Data: Integrates a dropdown list in the Product creation and editing forms to select categories, demonstrating how to bind and manage related data in forms.
Scaffolding: Uses scaffolding to generate controllers and views for CRUD operations, providing a quick and consistent way to create the necessary code for managing database entities.
Validation and User Feedback: Includes form validation and user feedback mechanisms to ensure data integrity and provide a good user experience.
Bootstrap Integration: Leverages Bootstrap for styling and responsive design, ensuring the application is visually appealing and functional on various devices.
NuGet Package Management: Manages dependencies through NuGet packages, including Entity Framework Core, SQL Server, and related tools.
How to Run
Clone the Repository:

bash
Copy code
git clone https://github.com/Rajesh9091/CRUD-with-Drop-Down-List
cd Rajesh9091
Open in Visual Studio:
Open the solution file (.sln) in Visual Studio 2022.

Restore NuGet Packages:
Visual Studio should automatically restore the required NuGet packages. If not, right-click on the solution and select "Restore NuGet Packages".

Update Database:
Configure your database connection string in appsettings.json and run the following commands in the Package Manager Console:

bash
Copy code
Add-Migration InitialCreate
Update-Database
Run the Application:
Press F5 or click on the "Start" button in Visual Studio to run the application.

Usage
Categories: Manage categories through the categories section where you can create, read, update, and delete categories.
Products: Manage products and associate them with categories using a dropdown list. You can create, read, update, and delete products.
This project serves as a comprehensive example for developers looking to understand and implement CRUD operations with related data in an ASP.NET Core MVC application. It is also a great starting point for building more complex web applications that require relational data handling.
