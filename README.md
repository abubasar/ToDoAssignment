# ToDoAssignment
## Challenge 1: Turning a ASP.NET Core Console Application into a Web API project
## Challenge 2: Creating a TODO REST API application
Using the Web API project template, build an application that can manage a TODO list.At this stage, you will store the data in a dictionary inside a separate singleton class. The endpoints are-
GET endpoint to list all items in the TODO list.
GET endpoint to return details of an individual item in the TODO list based on its unique identifier.
POST endpoint to insert a new item into the TODO list.
PUT endpoint to modify an existing item in the TODO list.
DELETE endpoint to remove an item from the TODO list.
## Challenge 3: Adding Entity Framework and a database
The application would look the same as in the previous challenge, but you will now store the data in a database
## Challenge 4: Moving ORM dependencies to a separate class library project
Refactor the application so the ORM (Entity Framework) components are managed by a class library rather than the main application.




## Challenge 5: Adding authentication and authorization
Next, we will need to do the authentication and authorization to our API application.The requirements are as follows:
Any anonymous user should be able to see the list of TODO items.
Only authenticated users should be able to view the details of each item.
Only the users with the admin role should be able to add, edit, or delete items from the list.
