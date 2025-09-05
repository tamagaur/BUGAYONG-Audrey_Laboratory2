3ISA - Laboratory Activity #2: CRUD API Implementation

In this project, we will create a simple REST API, built with **Express.js** and **MySQL**, where it manages student records and demonstrates full CRUD operations: Create, Read, Update, and Delete. This activity will help create clean project structures, database integration, and testing with Postman.

The server is powered by **Express.js**, while the data is stored in a **MySQL** database. 

**Step 1: Setup Database**
Create a new database in MySQL named **lab_crud**. Inside it, create the table:
1. students (id, name, age, course, created_at)
2. courses (id, code, title, units, created_at)


Verify the table using phpMyAdmin or MySQL CLI.

**Step 2: Build the Server**
Setup an Express.js server connected to MySQL. Configure your .env file with MySQL credentials. If successful, the terminal should display: 🚀 Server running… and ✅ MySQL connected.

**Step 3: Create Controllers**
Following clean project structure, build two controllers:
1. studentController.js - CRUD operations for students
2. courseController.js - CRUD operations for courses

Each controller must support all five operations:
1. Create (POST)
2. Read All (GET)
3. Read One (GET by ID)
4. Update (PUT)
5. Delete (DELETE)

**Step 4: Define Routes**
Create separate route files:
- studentRoutes.js mounted under /api/students
- coursesRoutes.js mounted under /api/courses

Update server.js to include both routes.

**Step 5: Test in Postman**
Perform a full CRUD cycle for **students and courses:**
- POST /api/students → Add a student
- GET /api/students → View all students
- GET /api/students/:id → View student by ID
- PUT /api/students/:id → Update a student
- DELETE /api/students/:id → Remove a course
- POST /api/courses → Add a course
- GET /api/courses → View all course
- GET /api/courses/:id → View course by ID
- PUT /api/coursess/:id → Update a course
- DELETE /api/courses/:id → Remove a course

Use Postman environment with **{{baseUrl}} for easier testing. 

**Step 6: Push to GitHub**
1. Initialize Git (if not already):
   git init
2. Add .gitignore to exclude node_modules and .env
3. Commit changes (e.g., Added CRUD API for students and courses).
4. Include .env.example (with placeholder values), but never upload your real .env.



