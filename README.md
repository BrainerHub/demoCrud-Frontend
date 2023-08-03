# Ete-service-frontend

## Prerequisites

- Node.js (v18.x), also npm 

## Local development

### 1. Install packages
```sh
npm i
```

### 2. Start server
```sh
npm run dev
```

Server will start on http://localhost:5173/

NodeJS backend + TS:
### Express server listening on localhost:3000, with 4 CRUD APIs:
### GET /employee/list
### POST /employee/create
### PUT /employee/update
### DEL /employee/delete
### ReactJS + TS frontend (make sure to add a header with a routing method):
### Main welcome page
### Employees page showing:
### Table listing all employees
### Add button => popup to add employee
### Edit button => open same popup and edit employee
### X icon on each row, on click => delete employee
### Each employee have:
### Full Name
### Email
### Age | DOB
### Country (drop down)
### Profile picture
### Data should be stored in a SQL database (local or free tier on the cloud).
### All data must be stored in JSON objects, hence, APIs outputs should be JSON formatted (can be done with express directly)