Advertisement Campaign Management System

Problem: Advertisement campaigns require controlled access to company funds. Without proper authorization and budget restrictions, unauthorized individuals could submit campaign requests or campaigns could exceed the available monthly budget.

Solution: The Advertisement Campaign Management System provides a centralized platform where authorized company employees can submit advertisement campaign requests within the available monthly budget. 

Project Features:
- Technologies: ASP.NET Core Razor Pages, C#, Entity Framework Core, and SQL Server.
- Role-Based Access Control (RBAC): Implemented three user roles—Manager, Employee, and Viewer—with different permissions for accessing and managing system resources.
- Authentication and Authorization: Used session-based authentication and a reusable SecurePageModel base class to centralize role validation and restrict unauthorized access.
- Dynamic UI Permissions: Controlled the visibility of navigation links and page actions based on the user's role.
- CRUD Operations: Implemented Create, Read, Update, and Delete operations for managing campaign requests, monthly budgets, and employee accounts according to role permissions.
- Data Filtering: Added filtering functionality to help users find specific records.
- Excel Export: Implemented functionality to export user data to Excel for reporting and record management.
- Security: Enforced server-side authorization to protect restricted pages and operations, independently of UI visibility.

![](https://github.com/Ln02323/The-Advertisement-Campaign-Management-System/blob/main/front.png?raw=true)
![](https://github.com/Ln02323/The-Advertisement-Campaign-Management-System/blob/main/camp%20list.png?raw=true)
![](https://github.com/Ln02323/The-Advertisement-Campaign-Management-System/blob/main/budget%20list.png?raw=true)
![](https://github.com/Ln02323/The-Advertisement-Campaign-Management-System/blob/main/emp%20list.png?raw=true)
![](https://github.com/Ln02323/The-Advertisement-Campaign-Management-System/blob/main/add%20camp.png?raw=true)
