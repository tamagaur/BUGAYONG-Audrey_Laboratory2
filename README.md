3ISA - Laboratory Activity #2: CRUD API Implementation

In this project, we will create a simple REST API, built with **Express.js** and **MySQL**, where it manages student records and demonstrates full CRUD operations: Create, Read, Update, and Delete. This activity will help create clean project structures, database integration, and testing with Postman.

The server is powered by **Express.js**, while the data is stored in a **MySQL** database. 

To setup the project, install the dependencies and configure your '.env' file with MySQL credentials.
Create the 'lab_crud' database and run the server. If successful, the terminal will show: `🚀 Server running…` and `✅ MySQL connected`.

The API provides endpoints for students:  
- `POST /api/students` → Add a student  
- `GET /api/students` → View all students  
- `GET /api/students/:id` → View student by ID  
- `PUT /api/students/:id` → Update a student  
- `DELETE /api/students/:id` → Remove a student

A supplemental part includes the same CRUD operations for courses. All endpoints should be tested in Postman using an environment with a `{{baseUrl}}` variable.  

For the documentation, a PDF file named `LastName_FirstName_Lab2.pdf` contains database screenshots, Postman results, and terminal logs will be provided. Also, the GitHub repository link is added, making sure `.env` is excluded but `.env.example` is included.  
