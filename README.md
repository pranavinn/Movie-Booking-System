<h1 align="center">Cinema-Booking</h1>

Movie ticket booking web application with MERN stack (MongoDB, Express, React, NodeJS) & Tailwind CSS


## Project Purpose
The purpose of this project is to improve my full-stack web development skills, learning front-end technologies like React and Tailwind CSS, and backend technologies like Node.js, Express, and MongoDB.

## Technologies
* React v18.2.0
* React Router Dom v6.14.2
* React Hook Form v7.45.4
* Tailwind CSS v3.3.3
* Vite v4.4.8
* NodeJS
* Mongoose v7.4.2
* Express v4.18.2
* MongoDB
* And more...



## Guide

### 🧩 Role / Feature

There are 3 roles on this website with corresponding permissions:

| Role  | Permisson / Feature |
|-------------|-------------|
|👀 Viewer (Not logged in)  | **1. View released showtimes by choosing from** <br> &emsp;- Movie in home page <br>  &emsp;- Cinema's theater in cinema page <br> &emsp;- Cinema's schedule in schedule page <br> **2. View released showtimes for today and the future** <br> **3. View seats for released showtimes on the showtime page**|
|👤 User   | **1. All Viewer permissions** <br> **2. Purchase tickets on the showtime page** <br> **3. View purchased tickets on the ticket page**|
|👑 Admin   | **1. All User permissions** <br> **2. View all showtimes for any date** <br> **3. Manage cinemas** <br> **4. Manage theaters** <br> &emsp;- View theater's row, column, seats information <br> **5. Manage showtimes** <br> &emsp;- Search & filter & sort showtimes <br> &emsp;- View details of booked seats <br> **6. Manage movies** <br> **7. Manage user & admin**|

### 👀 Viewer
Viewer have access to these pages for viewing released showtimes.





### 👤 User
User have all viewer permission. Including, the ability to purchase and view their own tickets



### 👑 Admin
Admin have all permission.



1. Register a new user.
2. Access MongoDB and locate the user's data.
3. Update the user's role to `admin`.
4. The user will now become admin.


## How to run the app
1. Download the code
2. Create .env file in /server
```
PORT=8080
DATABASE=<your MongoDB connection string URI>
JWT_SECRET=<any random JWT secret>
JWT_EXPIRE=30d
JWT_COOKIE_EXPIRE=30
```
3. Start server side
```
cd server
npm install
npm start
```
4. Start client side
```
cd client
npm install
npm run dev
```
