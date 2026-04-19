# Backend API (Express + Sequelize)

## Description
Simple backend project using Express and Sequelize.
Manages Users and Posts with a one-to-many relationship.

---

## Setup
1. Install dependencies:
npm install

2. Run migrations:
npx sequelize db:migrate

3. Start server:
npm start

---

## Run
http://localhost:3000

---

## APIs

Users:
GET /users  
GET /users/:id  
POST /users  
PUT /users/:id  
DELETE /users/:id  

Posts:
GET /posts  
GET /posts/:id  
POST /posts  
PUT /posts/:id  
DELETE /posts/:id  

---

## Sample Request

POST /users
{
  "name": "Ali",
  "email": "ali@gmail.com"
}

---

## Relationship
One User has many Posts  
Each Post belongs to one User  
