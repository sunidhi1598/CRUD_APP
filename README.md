CRUD App

It supports full CRUD operations (Create, Read, Update, Delete) project built using:

Node.js

Express.js

MongoDB

Mongoose

Postman (for API testing)

Simple HTML frontend

🚀 Features

Add new task

View all tasks

Update task

Delete task

Connected with MongoDB database

Tested using Postman

Installation & Setup
1️⃣ Install Node.js

Download and install Node.js from official website.

Check version:

node -v
npm -v

2️⃣ Install MongoDB

Install MongoDB Community Server and start the MongoDB service.

3️⃣ Clone the Project
git clone <your-github-repo-link>
cd crud-app

4️⃣ Install Dependencies
npm install

5️⃣ Create .env File

Create a file named .env in root folder and add:

PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/crudDB

6️⃣ Run the Server
node server.js


OR (if nodemon installed)

nodemon server.js


Server will run on:

http://localhost:5000

API Endpoints
➤ Create Task

POST /api/tasks

➤ Get All Tasks

GET /api/tasks

➤ Get Single Task

GET /api/tasks/:id

➤ Update Task

PUT /api/tasks/:id

➤ Delete Task

DELETE /api/tasks/:id

Testing with Postman

Open Postman

Use http://localhost:5000/api/tasks

Select method (GET, POST, PUT, DELETE)

For POST/PUT use JSON body

Example:

{
  "title": "Prepare for Machine Test"
}

Frontend

Open index.html in browser.
You can add and delete tasks from UI.

Project Structure
crud-app/
│
├── server.js
├── .env
├── models/
│     └── Task.js
├── routes/
│     └── taskRoutes.js
└── index.html

Purpose

This project is created for:

Practice CRUD operations

Understanding MongoDB connection

Preparing for Machine Test / Interview

👩‍💻 Author

Sunidhi Kumari

